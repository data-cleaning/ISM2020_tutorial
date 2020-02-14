# EESW2019_tutorial

<a href="https://www.amazon.com/Statistical-Data-Cleaning-Applications-R/dp/1118897153"><img align="right" src="src/00tex/sdcr.jpg" width=200></a>

Materials for the short course on Statistical Data Cleaning for Business
Statistics at the 
[European Establishment Statistics Workshop 2019](https://statswiki.unece.org/display/ENBES/EESW19)


----

### Contents 

Slot 1 

|Topic                 | time (m)  |
|----------------------|-----------|
|Introduction          | 20        |
|Reading dirty data    | 30        |
|Approximate matching  | 50        |
|Data validation       | 50        |


Slot 2 


|Topic                 | time (m)  |
|----------------------|-----------|
| Error localization   | 20        |
| Imputation           | 50        |
| Adjusting            | 20        |
| Monitoring           | 30        |
| Wrap-up              | 10        |

### Course form

The course form is highly hands-on. Each topic starts with an approximately
10-15 minute session where you run and adapt some R code. Next, I will provide
background and details on what you just did. After that there is a more
in-depth assignment. Depending on time and topic we will discuss the topic more
in-depth after that.




### Prerequisites

**Bring a laptop**

Participants are expected to have a basic knowledge of R/RStudio, explicitly:

- Work with the R command line and R scripts
- Read/write CSV data
- Some basic data manipulations and plots
- I highly recommend working with RStudio projects.

### Software needed for the course

1. R See [https://r-project.org](https://r-project.org)
2. (Recommended) [Rstudio](https://rstudio.com)

Execute the following R code to install the necessary packages.

```r
install.packages(c(
        "validate"
      , "errorlocate"
      , "simputation"
      , "rspa"
      , "daff"
      , "jsonlite"
      , "XML"
      , "readr"
      , "stringr"
      , "lumberjack")
  , dependencies=TRUE)
```

----
## License

[![Creative Commons License](https://i.creativecommons.org/l/by-nc/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/).



