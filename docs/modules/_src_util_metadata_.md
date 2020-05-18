[@substrate/txwrapper](../README.md) › [Globals](../globals.md) › ["src/util/metadata"](_src_util_metadata_.md)

# Module: "src/util/metadata"

## Index

### Interfaces

* [ChainProperties](../interfaces/_src_util_metadata_.chainproperties.md)

### Functions

* [getRegistry](_src_util_metadata_.md#getregistry)

## Functions

###  getRegistry

▸ **getRegistry**(`chainName`: "Kusama" | "Polkadot" | "Westend", `specName`: "kusama" | "polkadot" | "westend", `specVersion`: number): *TypeRegistry*

*Defined in [src/util/metadata.ts:64](https://github.com/paritytech/txwrapper/blob/2ba8a31/src/util/metadata.ts#L64)*

Given a chain name, a spec name, and a spec version, return the
corresponding type registry. This function only returns the correct type
registry for the following chains:
- Kusama,
- Polkadot,
- Westend.
For other chains, please use `@polkadot/api`s `TypeRegistry` directly.

**`see`** https://github.com/polkadot-js/api/tree/master/packages/types-known

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`chainName` | "Kusama" &#124; "Polkadot" &#124; "Westend" | The chain to create the type registry for. Returned by RPC `system_chain`. |
`specName` | "kusama" &#124; "polkadot" &#124; "westend" | The name of the runtime spec. Returned by RPC `state_getRuntimeVersion`. |
`specVersion` | number | The spec version of that chain for which we want to create a type registry. Returned by RPC `state_getRuntimeVersion`.  |

**Returns:** *TypeRegistry*