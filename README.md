# R Testing

# Installation:
- Install R for you [specific host enviornment](https://cran.r-project.org/bin/).
- Clone this repo and `$ cd r_testing`
- Run these R commands:

``` 
r_testing $ r
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
