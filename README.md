# Symbolic verification of SPEKE protocols
Verification of the design of the SPEKE protocols in many variants including the original and the latest ISO standard

## Description & Discussion

At the following link you can find detailed discussion in the paper:
- [Analyzing and Patching SPEKE in ISO/IEC](https://doi.org/10.1109/TIFS.2018.2832984) published at IEEE Transactions on Information Forensics and Security in 2018.

## Basics

Once you succesfully install proverif (1.97), scripts can be veified running the following:

```
    proverif <file>.pv
```

For those verifications which lead to attacks, you may want to have a look in eventually generated schemes by calling ProVerif with the flag `-graph` and a directory of choice where PDF will be generated.

```
    proverif -graph <some-directory> <file>.pv
```
