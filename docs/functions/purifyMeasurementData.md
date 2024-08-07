[**motoko-benchmarking-ts v1.0.0**](../README.md) • **Docs**

***

[motoko-benchmarking-ts v1.0.0](../globals.md) / purifyMeasurementData

# Function: purifyMeasurementData()

> **purifyMeasurementData**(`data`, `base`): [`MeasurementData`](../type-aliases/MeasurementData.md)

A function for when you need to know the pure resource usage of operation by substracting usage of needed utils

## Parameters

• **data**: [`MeasurementData`](../type-aliases/MeasurementData.md)

Measurement data for the function that you want to measure

• **base**: [`MeasurementData`](../type-aliases/MeasurementData.md)

Measurement data for the function that has other operations that are inside IC.countInstructions()

## Returns

[`MeasurementData`](../type-aliases/MeasurementData.md)

if the measurement failed - returns all zeroes, substracts all values except for rts_mutator_instructions

## Example

```ts
When you have a batch element adding function like pseudocode: "public func batch_add() {for (i in 0..100) {Map.add(i)}}". You are using for loop to add elements to a map and you want to know how much resources only the data structure uses and not for loop. You can make a for_loop() function like: "public func for_loop() {for (i in 0..100) {}}" in the canister and measure it's resource usage. Then you can substract usage of for_loop() from batch_add() function and you will get the pure resource usage of data structure map
```

## Defined in

[index.ts:148](https://github.com/ktry1/motoko-benchmarking-ts/blob/358ac8e3b4570fb43e76bccebf75f01c614e08ff/index.ts#L148)
