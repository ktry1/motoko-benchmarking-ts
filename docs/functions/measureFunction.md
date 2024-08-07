[**motoko-benchmarking-ts v1.0.0**](../README.md) • **Docs**

***

[motoko-benchmarking-ts v1.0.0](../globals.md) / measureFunction

# Function: measureFunction()

> **measureFunction**\<`T`\>(`actor`, `fn`, `args`): `Promise`\<[`MeasurementData`](../type-aliases/MeasurementData.md)\>

## Type Parameters

• **T** *extends* (...`args`) => `Promise`\<`bigint`\>

## Parameters

• **actor**: `any`

an actor that will be used to interact with a local canister

• **fn**: `T`

a function of the actor that will be called

• **args**: `Parameters`\<`T`\>

arguments to the called function

## Returns

`Promise`\<[`MeasurementData`](../type-aliases/MeasurementData.md)\>

MeasurementData object

## Defined in

[index.ts:242](https://github.com/ktry1/motoko-benchmarking-ts/blob/358ac8e3b4570fb43e76bccebf75f01c614e08ff/index.ts#L242)
