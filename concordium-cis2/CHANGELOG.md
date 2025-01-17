# Changelog

## Unreleased changes

## concordium-cis2 5.0.0 (2023-08-21)

- Derive `PartialEq` and `Eq` for the `TransferEvent`, `MintEvent`, `BurnEvent`, `UpdateOperatorEvent`, `TokenMetadataEvent`, `OperatorUpdate`, and `UpdateOperator` types.
- Added `Cis2Client` to the library. This can be used from one smart contract to
  call into other cis2 compatible smart contracts in a type safe way.
- Bump concordium-std to version 8.


## concordium-cis2 4.0.0 (2023-06-16)

- Bump concordium-std to version 7.
p
## concordium-cis2 3.1.0 (2023-05-08)

- Derive `PartialEq` and `Eq` for the `MetadataUrl` from the CIS2 library.
- Update `concordium-std` dependency to 6.2.

## concordium-cis2 3.0.0 (2023-02-08)

- Update `concordium-std` to version 6.

## concordium-cis2 2.0.0 (2022-11-21)

- Update `concordium-std` to version 5.
- Add `From` implementation from types implementing `From<UpgradeError>`, `From<QueryAccountBalanceError>` or `From<QueryContractBalanceError>` to `Cis2Error`.
- Add SchemaType for Cis2Event<T, A>

## concordium-cis2 1.2.0 (2022-09-01)

- Add `TokenAmountU256`
- Fix overflow during deserialization of amounts.

## concordium-cis2 1.1.0 (2022-08-24)

- Update `concordium-std` to version 4.
- Support schemas for error types defined in the library.

## concordium-cis2 1.0.0

Initial release of the library.
