[@substrate/txwrapper](../README.md) › [Globals](../globals.md) › ["src/methods/democracy/closeProxy"](_src_methods_democracy_closeproxy_.md)

# Module: "src/methods/democracy/closeProxy"

## Index

### Functions

* [closeProxy](_src_methods_democracy_closeproxy_.md#closeproxy)

## Functions

###  closeProxy

▸ **closeProxy**(`args`: object, `info`: [BaseTxInfo](../interfaces/_src_util_types_.basetxinfo.md), `options`: [OptionsWithMeta](../interfaces/_src_util_types_.optionswithmeta.md)): *[UnsignedTransaction](../interfaces/_src_util_types_.unsignedtransaction.md)*

*Defined in [src/methods/democracy/closeProxy.ts:16](https://github.com/paritytech/txwrapper/blob/ef571f4/src/methods/democracy/closeProxy.ts#L16)*

Clear the proxy. Called by the proxy.

**`deprecated`** Update to the latest version of Substrate to use the proxy pallet.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`args` | object | Arguments specific to this method. |
`info` | [BaseTxInfo](../interfaces/_src_util_types_.basetxinfo.md) | Information required to construct the transaction. |
`options` | [OptionsWithMeta](../interfaces/_src_util_types_.optionswithmeta.md) | Registry and metadata used for constructing the method. |

**Returns:** *[UnsignedTransaction](../interfaces/_src_util_types_.unsignedtransaction.md)*
