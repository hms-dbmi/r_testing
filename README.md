# R Testing [![Build Status](https://travis-ci.org/scottx611x/r_testing.svg?branch=master)](https://travis-ci.org/scottx611x/r_testing)

## Installation:
- Install R for you [specific host enviornment](https://cran.r-project.org/bin/).
- Clone this repo and `$ cd r_testing`

## Running Tests
- Run these R commands:

``` 
> install.packages("devtools", dependencies = TRUE)
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
    - Run the prior check against 3 different R versions.
    - Make new releases on Github when you introduce a tag
    - Send an email if these prior checks fail