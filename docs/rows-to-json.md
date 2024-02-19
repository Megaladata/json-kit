# Rows to JSON

[Back to the list of components](../README.md)

## Purpose

The component converts table rows into an array or list of JSON format objects.

## Input Ports

| Name                     | Type       |
|:-------------------------|:-----------|
| Input Dataset        | Table      |
| Variables                | Variables  |

### "Input Data Source" Table Structure

The table structure is not defined, auto-synchronization is enabled in the port.

### Variables in the "Variables" Port

| № | Caption | Type     | Value    |
|:--|:--------------|:-----------------|:---------|
| 1 | JSON String Type  | ![](./img/string.svg) String      | arr |

**JSON Row Type** accepts values:

* **arr** (default) — conversion to a JSON array;
* **obj** — conversion to a list of JSON objects.

## Output Ports

| Name                     | Type        |
|:-------------------------|:------------|
| Output Dataset          | Table       |

### "Output Dataset" Table Structure

| Caption        | Type         | Description       |
|:-------------|:--------------|:--------------|
| JSON Row     | ![](./img/string.svg) String              | Result of converting the dataset into a JSON string  |
