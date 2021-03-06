## Topsis-Mahek-101903567

--Calculate TOPSIS Score and rank them.

## Installation

```sh
>> pip install Topsis-Mahek-101903567==1.0.1
```

## How to use it?

```sh
>> TOPSIS data.csv "1,1,1,2,2" "+,+,-,+,+" result.csv
```

## Input File (data.csv)

- Input file must contain 3 or more columns.
- First column is the object/variable name (e.g. M1, M2, M3, M4, M5, M6, M7, M8).
- From 2nd to last columns must contain numeric values only.

## Output File (result.csv)

Result file contains all the columns of input file and 2 additional columns having Topsis Score and Rank.

## Check the following-

- Number of weights, number of impacts and number of columns (from 2nd to last columns) must be same.
- Impacts must be either +ve or -ve.
- Impacts and weights must be separated by ',' (comma).

## License

2022 Mahek Khowala
This repository is licensed under the MIT license. See LICENSE for details.
