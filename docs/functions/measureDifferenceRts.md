[**motoko-benchmarking-ts v1.0.0**](../README.md) • **Docs**

***

[motoko-benchmarking-ts v1.0.0](../globals.md) / measureDifferenceRts

# Function: measureDifferenceRts()

> **measureDifferenceRts**(`new_values`, `prev_values`): [`RtsData`](../type-aliases/RtsData.md)

A function to measure the difference between the RtsData before and after update function call.

## Parameters

• **new\_values**: [`RtsData`](../type-aliases/RtsData.md)

rts values measured after calling an update function

• **prev\_values**: [`RtsData`](../type-aliases/RtsData.md)

rts values measured before calling an update function

## Returns

[`RtsData`](../type-aliases/RtsData.md)

## Note

instruction_count and rts_mutator_instructions are not substracted because they are measured not accumulatively, but only for the last update function call

## Defined in

[index.ts:127](https://github.com/ktry1/motoko-benchmarking-ts/blob/358ac8e3b4570fb43e76bccebf75f01c614e08ff/index.ts#L127)
