# Columns to JSON

[Back to the list of components](../README.md)

## Purpose

The component converts table columns into a JSON format array. The processing result for each column is recorded in a separate row.

## Input Ports

| Name                     | Type       |
|:-------------------------|:-----------|
| Input Data Source        | Table      |
| Variables                | Variables  |

### "Input Dataset" Table Structure

The table structure is not defined, auto-synchronization is enabled in the port.

### Variables in the "Variables" Port

| № | Caption       | Type            | Value   |
|:--|:------------|:------------------------------------|:--------|
| 1 | IncludeKey         | ![](./img/logical.svg) Logical      | true    |

**Key** accepts values:

* **true** (default) — uses the column name as a key for the array;
* **false** — the array is returned without a key.

## Output Ports

| Name                     | Type        |
|:-------------------------|:------------|
| Output Dataset          | Table       |

### "Output Dataset" Table Structure

| Caption        | Type         | Description          |
|:-------------|:--------------------|:---------------------------|
| JSON Row     | ![](./img/string.svg) String              | Result of converting the dataset into a JSON string  |
