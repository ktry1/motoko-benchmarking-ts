[**motoko-benchmarking-ts v1.0.0**](../README.md) • **Docs**

***

[motoko-benchmarking-ts v1.0.0](../README.md) / saveToExcelRts

# Function: saveToExcelRts()

> **saveToExcelRts**(`file_path`, `sheet_names`, `headers`, `data`): `Promise`\<`void`\>

A function to save 2D array of RtsData to the excel file. Useful if you want to only measure rts values and not instruction count from ExperimentalInternetComputer.countInstructions()

## Parameters

• **file\_path**: `string`

that full path to the file that will be saved. example: "./tests/map.xlsx"

• **sheet\_names**: `string`[]

array of sheet names that will be in a new excel file

• **headers**: `string`[]

array of headers that the sheets will have

• **data**: [`RtsData`](../type-aliases/RtsData.md)[][]

{RtsData[][]} - 2D array of RtsData

## Returns

`Promise`\<`void`\>

## Defined in

index.ts:339
