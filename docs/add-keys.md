# Adding Keys

[Back to the list of components](../README.md)

## Purpose

The component adds keys up to the second level of nesting and curly brackets (optionally) to a JSON string.

## Input Ports

| Name                     | Type       |
|:-------------------------|:-----------|
| Input dataset      | Table      |
| Variables                | Variables  |

### "Input dataset" Table Structure

| Caption        | Type     | Description                       |
|:-------------|:-------|:----------------------------------|
| JSON Row  | ![](./img/string.svg) String              | Dataset in JSON format           |

### Variables in the "Variables" Port

| № | Caption         | Type            | Value   |
|:--|:---------------------------|:-------------|:--------|
| 1 | First Level Key Name       | ![](./img/string.svg) String        | DataSet |
| 2 | Second Level Key Name      | ![](./img/string.svg) String        | Rows    |
| 3 | Curly Brackets             | ![](./img/logical.svg) Logical      | true    |

1. The variables **First Level Key Name** and **Second Level Key Name** add keys up to the second level of nesting to the JSON string. If the value of one of the variables is empty, the variable with the specified value will be considered the first-level key.

2. The variable **Curly Brackets** adds opening and closing curly brackets to the original JSON string when the flag is enabled. The default is **true**.

## Output Ports

| Name                     | Type        |
|:-------------------------|:------------|
| Output dataset          | Table       |

### "Output Dataset" Table Structure

| Caption        | Type     | Description     |
|:-------------|:----|:------------------------|
| JSON Row  | ![](./img/string.svg) String              | Result of converting the dataset into a JSON string  |