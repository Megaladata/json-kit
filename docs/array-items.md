# JSON Array Elements

[Back to the list of components](../README.md)

## Purpose

The component returns all elements of a JSON array.

## Input Ports

| Name                     | Type       |
|:-------------------------|:-----------|
| Input dataset      | Table      |
| Variables                | Variables  |

### "Input dataset" Table Structure

| Caption        | Type           | Description     |
|:-------------|:----------|:----------------------------------|
| JSON Row  | ![](./img/string.svg) String              | Dataset in JSON format           |

### Variables in the "Variables" Port

| № | Caption      | Type               | Value   |
|:--|:---------------------|:---------|:--------|
| 1 | Column Name          | ![](./img/string.svg) String      | Items   |

## Output Ports

| Name                     | Type        |
|:-------------------------|:------------|
| Output dataset          | Table       |

### "Output dataset" Table Structure

A dataset consisting of a single column with array elements.
