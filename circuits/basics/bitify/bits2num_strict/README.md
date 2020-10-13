# `Bits2Num_strict()`

## Description

This template converts a binary number `in[n]` of `n` bits to its
integer representation STRICT <!--- TODO: Add strict description. -->

## Schema

```
             _____________________     
            |                     |
in[n] ----> |  Bits2Num_strict()  | ----> out
            |_____________________|     
```


## Dependencies

```
include "../../comparators/alias_check/alias_check.circom";
include "../bits2num/bits2num.circom";
```

## Expected Inputs

| Input              | Type                      | Representation             |
| -------------      | -------------             | -------------      | 
| `in[254]`            | Binary array of `254` bits  |  The encoding is expected in the [LSB 0 bit numbering](https://en.wikipedia.org/wiki/Bit_numbering#LSB_0_bit_numbering). |

## Outputs

| Output           | Type          | Description     |
| -------------    | ------------- | ----------      | 
| `out`            | Field element | Integer representation of the binary number `in`.  |

## Benchmarks 

## Test