# Symbolic verification of SPEKE protocols
Verification of the design of the SPEKE protocols in many variants including the original and the latest ISO standard

Once you succesfully install proverif, scripts can be veified running the following:

```
    proverif <file>.pv
```

For those verifications which lead to attacks, you may want to have a look in eventually generated schemes by calling ProVerif with the flag `-graph` and a directory of choice where PDF will be generated.

```
    proverif -graph <some-directory> <file>.pv
```
