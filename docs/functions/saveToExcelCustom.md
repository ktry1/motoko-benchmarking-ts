[**motoko-benchmarking-ts v1.0.0**](../README.md) • **Docs**

***

[motoko-benchmarking-ts v1.0.0](../README.md) / saveToExcelCustom

# Function: saveToExcelCustom()

> **saveToExcelCustom**\<`T`\>(`file_path`, `rows`, `sheet_names`, `headers`, `data`): `Promise`\<`void`\>

A function to save your custom data type to excel table. Useful if you want to conduct your own tests with different properties.

## Type Parameters

• **T** *extends* `Record`\<`string`, `unknown`\>

## Parameters

• **file\_path**: `string`

that full path to the file that will be saved. example: "./tests/map.xlsx"

• **rows**: `string`[]

• **sheet\_names**: `string`[]

array of sheet names that will be in a new excel file

• **headers**: `string`[]

array of headers that the sheets will have

• **data**: `T`[][]

{YourDataType[][]} - 2D array of your custom data type objects

## Returns

`Promise`\<`void`\>

## Defined in

index.ts:361
