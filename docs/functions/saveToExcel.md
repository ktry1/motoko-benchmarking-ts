[**motoko-benchmarking-ts v1.0.0**](../README.md) • **Docs**

***

[motoko-benchmarking-ts v1.0.0](../globals.md) / saveToExcel

# Function: saveToExcel()

> **saveToExcel**(`file_path`, `sheet_names`, `headers`, `data`): `Promise`\<`void`\>

A function to save 2D array of MeasurementData to the excel file.

## Parameters

• **file\_path**: `string`

that full path to the file that will be saved. example: "./tests/map.xlsx"

• **sheet\_names**: `string`[]

array of sheet names that will be in a new excel file

• **headers**: `string`[]

array of headers that the sheets will have

• **data**: [`MeasurementData`](../type-aliases/MeasurementData.md)[][]

{MeasurementData[][]} - 2D array of MeasurementData obtained from measureFunction()

## Returns

`Promise`\<`void`\>

## Defined in

[index.ts:318](https://github.com/ktry1/motoko-benchmarking-ts/blob/358ac8e3b4570fb43e76bccebf75f01c614e08ff/index.ts#L318)
