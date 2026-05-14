# CCSV
Another CLearning crossover. This repository is part of CLearning's ecosystem and was made to help other tool's development. If you find it useful, use it. In summary, CCSV is a simple header-only csv parser library.

## Functions
- **Parse**: Returns a List of all the values in the csv, supports ';', ',', and '|' separators.

## Dependencies (optional)
- **CList**
- **Ariadne**

## Technical details
If you want to use the List value it was originally designed for, you must use the next #define
```c
    #define USE_CLIST
    #include <ccsv.h>
```

Otherwise, you can just include it normally

## Install instructions
Download it from this repository and add the header to your project or use `cl -i ccsv-nodep` or `cl -i ccsv` in your console if you have CLearning installed.

### Version
1.0.0 - CCSV, .csv parser
Author: Nahum Naranjo