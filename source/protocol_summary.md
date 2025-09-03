Bulla Network enables the on-chain creation of credit pools for invoice factoring. By adhering to the **ERC4626** specification, permissioned depositors can earn interest for facilitating invoice funding. Through these contracts, invoice issuers can factor their receivables, allowing them to receive early payments in exchange for a premium. This integration not only broadens the utility of the Bulla Claim Protocol but also provides a new financial mechanism for liquidity and credit management on-chain.

This audit update introduces _several_ new features:
 - The ability to queue redemptions/withdrawals from the pool in a FIFO order.
 - A new controller pattern which allows for specialized contracts to completely control the claims they create, enabling:
    - Extended functionality: beyond basic claim operations (interest calculations, complex payment flows, etc.)
    - Custom business logic: for specific use cases (lending, invoicing, etc)
    - Additional states and workflows: tailored to different financial instruments
    - Domain-specific features: while maintaining core claim properties
 - The protocol uses an EIP712-based approval system that allows users to grant specific permissions to controllers without requiring multiple transactions. This enables gasless interactions and streamlined user experiences while maintaining security.

These new features make Bulla Network much more extensible as the team can introduce new contracts which inherit the base controller implementation.