## Hackathon KMS 2018

**Athor** : kitokip
**Date**: 12/07/2018
**Mission**: Solve SG Flood problem

## DETAIL

* Input: 
    * {String} S - with length = N (k x k flood)
    * EX: "1100000110000001100000001111000011000010100000011"
* Flood Area: 

| Area | 0     | 1    | 2   | 3     | 4    | 5    | 6    |
| ---- | :---: | ---: | --- | :---: | ---: | ---: | ---: |
| 0    | 1     | 1    | 0   | 0     | 0    | 0    | 0    |
| 1    | 1     | 1    | 1   | 0     | 0    | 0    | 0    |
| 2    | 0     | 1    | 1   | 0     | 0    | 0    | 0    |
| 3    | 0     | 0    | 0   | 1     | 1    | 1    | 1    |
| 4    | 0     | 0    | 0   | 1     | 1    | 1    | 0    |
| 5    | 0     | 0    | 0   | 1     | 1    | 1    | 1    |
| 6    | 0     | 0    | 0   | 1     | 0    | 1    | 1    |

* Solution: The Area need to iolation is the area that have max sum of row