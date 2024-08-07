[**motoko-benchmarking-ts v1.0.0**](../README.md) • **Docs**

***

[motoko-benchmarking-ts v1.0.0](../globals.md) / MeasurementData

# Type Alias: MeasurementData

> **MeasurementData**: `object`

Represents the data structure for measuring resource usage.

## Type declaration

### instruction\_count

> **instruction\_count**: `bigint`

Wasm instructions used by operations measured with ExperimentalInternetComputer.countInstructions()

### rts\_collector\_instructions

> **rts\_collector\_instructions**: `bigint`

Wasm instructions used by garbage collector in the last update function call

### rts\_heap\_size

> **rts\_heap\_size**: `bigint`

size of used heap memory in bytes

### rts\_memory\_size

> **rts\_memory\_size**: `bigint`

total memory size of a canister in bytes

### rts\_mutator\_instructions

> **rts\_mutator\_instructions**: `bigint`

total Wasm instructions used by the last called update function, except for garbage collection

### rts\_reclaimed

> **rts\_reclaimed**: `bigint`

all time accumulative amount of memory reclaimed in bytes

### rts\_stable\_memory\_size

> **rts\_stable\_memory\_size**: `bigint`

size of used stable memory in 65536 bytes pages

### rts\_total\_allocation

> **rts\_total\_allocation**: `bigint`

all time accumulative amount of memory allocated in bytes

## Defined in

[index.ts:31](https://github.com/ktry1/motoko-benchmarking-ts/blob/358ac8e3b4570fb43e76bccebf75f01c614e08ff/index.ts#L31)
