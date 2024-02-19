# JSON Parsing

[Back to the list of components](../README.md)

## Purpose

The component converts a JSON string into a tabular dataset.

## Input Ports

| Name                     | Type       |
|:-------------------------|:-----------|
| Input dataset       | Table      |

### "Input Dataset" Table Structure

| Caption        | Type     | Description                       |
|:-------------|:-------------|:----------------------------------|
| JSON Row  | ![](./img/string.svg) String              | Dataset in JSON format           |

## Output Ports

| Name                     | Type        |
|:-------------------------|:------------|
| Output dataset          | Table       |

### "Output dataset" Table Structure

The table structure depends on the structure of the dataset in JSON format.
