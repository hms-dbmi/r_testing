# R Testing [![Build Status](https://travis-ci.org/hms-dbmi/r_testing.svg?branch=master)](https://travis-ci.org/hms-dbmi/r_testing) [![codecov](https://codecov.io/gh/hms-dbmi/r_testing/branch/master/graph/badge.svg)](https://codecov.io/gh/hms-dbmi/r_testing)


## Installation:
- Install R for you [specific host enviornment](https://cran.r-project.org/bin/).
- Clone this repo change directory into: `r_testing`
- Install R devtools: 
``` r
> install.packages("devtools", dependencies = TRUE)`
```

## Running Tests
``` r
> devtools::test()
```
- The example test should run and you will see output like so:
```
Loading RTesting
Testing RTesting
Hello World Test: .

DONE ===========================================================================
```

## Continuous Integration:
- See the [`.travis.yml`](https://github.com/scottx611x/r_testing/blob/master/.travis.yml) file in this directory for information on what the CI process will do.

#### In short, this will:
    - Check the R code and package structure for consistency with R's best practices.
    - Run the prior checks against 3 different R versions.
    - Upload R code coverage information to CodeCov
    - Send an email if these prior checks fail
