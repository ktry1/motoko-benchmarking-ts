[**motoko-benchmarking-ts v1.0.0**](../README.md) • **Docs**

***

[motoko-benchmarking-ts v1.0.0](../README.md) / measureDifference

# Function: measureDifference()

> **measureDifference**(`new_values`, `prev_values`, `instruction_count`): [`MeasurementData`](../type-aliases/MeasurementData.md)

A function to measure the difference between the MeasurementData before and after update function call.

## Parameters

• **new\_values**: [`RtsData`](../type-aliases/RtsData.md)

rts values measured after calling an update function

• **prev\_values**: [`RtsData`](../type-aliases/RtsData.md)

rts values measured before calling an update function

• **instruction\_count**: `bigint`

Wasm instruction count of operations measured with ExperimentalInternetComputer.countInstructions()

## Returns

[`MeasurementData`](../type-aliases/MeasurementData.md)

MeasurementData object

## Note

instruction_count and rts_mutator_instructions are not substracted because they are measured not accumulatively, but only for the last update function call

## Defined in

index.ts:106