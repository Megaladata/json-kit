# JSON Union

[Back to the list of components](../README.md)

## Purpose

The component merges JSON strings, separating them by commas, into a single JSON string enclosed in curly brackets.

## Input Ports

| Name                      | Type       |
|:--------------------------|:-----------|
| Input dataset        | Table      |
| Input dataset 2       | Table      |

The component can work with any number of ports of the Table type (default is 2).

### "Input Dataset" Table Structure

The table structure is not defined, auto-synchronization is enabled in the port.

### "Input Dataset 2" Table Structure

The table structure is not defined, auto-synchronization is enabled in the port.

## Output Ports

| Name                     | Type        |
|:-------------------------|:------------|
| Output dataset          | Table       |

### "Output Dataset" Table Structure

| Caption        | Type         | Description  |
|:-------------|:-------|:---------------|
| JSON Row | ![](./img/string.svg) String              | Result of merging JSON strings into one common JSON string|
