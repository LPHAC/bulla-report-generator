The audit was started on commits [063ed28](https://github.com/bulla-network/factoring-contracts/blob/063ed28aae97f6f5ffbc3c75a9b981ac89995c1e) and [256561d](https://github.com/bulla-network/bulla-contracts-V2/blob/256561d6a7a214975de9146503e54cf89362736c) for **7** days. A subsequent fix review was conducted on final commits [b003dca](https://github.com/bulla-network/factoring-contracts/blob/b003dca99a9094a231988f27f1ed74cff78e8de7) and [070653f](https://github.com/bulla-network/bulla-contracts-V2/blob/070653fe0e54b8481bb5e45c8ba04884fa5496e4) that went for **1** day.

The following contracts were included as part of the review scope, including any related external dependencies:

## factoring-contracts

```text
factoring-contracts/
|-- contracts/
    |-- BullaClaimV2InvoiceProviderAdapterV2.sol
    |-- BullaFactoring.sol
    |-- RedemptionQueue.sol
    \-- interfaces/
        |-- IBullaFactoring.sol
        |-- IERC20.sol
        |-- IInvoiceProviderAdapter.sol
        \-- IRedemptionQueue.sol
```

## bulla-contracts-v2

```text
bulla-contracts-v2/
|-- src/
    |-- BullaApprovalRegistry.sol
    |-- BullaClaimControllerBase.sol
    |-- BullaClaimV2.sol
    |-- BullaControllerRegistry.sol
    |-- BullaFrendLendV2.sol
    |-- BullaInvoice.sol
    |-- interfaces/
    |   |-- IBullaApprovalRegistry.sol
    |   |-- IBullaClaimAdmin.sol
    |   |-- IBullaClaimCore.sol
    |   |-- IBullaClaimV2.sol
    |   |-- IBullaControllerRegistry.sol
    |   |-- IBullaFrendLendV2.sol
    |   |-- IBullaInvoice.sol
    |-- libraries/
    |   |-- BullaClaimPermitLib.sol
    |   |-- BullaClaimValidationLib.sol
    |   \-- CompoundInterestLib.sol
    \-- types/
        \-- Types.sol
```
