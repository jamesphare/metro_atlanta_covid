---
title: "Metro Atlanta COVID"
output: 
  html_document: 
    keep_md: yes
---



I wanted a better visualization of local Covid-19 data than I've been able to 
find, particularly in terms of the distribution of cases and deaths
as they change over time. The charts below track confirmed cases and deaths in 
the core Metro Atlanta counties, both in absolute and relative terms. The 
subsequent charts track new cases and deaths in Metro Atlanta, Georgia, and the 
United States.

All data come from the New York Times' ongoing [repository](https://github.com/nytimes/covid-19-data) 
of Covid-19 cases and deaths in the United States.

It's hard to know how to interpret these numbers since there are major known
unknowns. Neither confirmed cases nor deaths can be said to be reliable counts
of the true numbers.

# Metro Atlanta

## Total Cases by County

![](Metro_Atlanta-_COVID_files/figure-html/atl_cases_absolute-1.png)<!-- -->

## Total Deaths by County

![](Metro_Atlanta-_COVID_files/figure-html/atl_deaths_absolute-1.png)<!-- -->

## Cases per Thousand by County

![](Metro_Atlanta-_COVID_files/figure-html/atl_relative_cases-1.png)<!-- -->

## Deaths per Thousand by County

![](Metro_Atlanta-_COVID_files/figure-html/alt_relative_deaths-1.png)<!-- -->

## New Cases in Metro Atlanta


```
## `geom_smooth()` using method = 'loess' and formula 'y ~ x'
```

![](Metro_Atlanta-_COVID_files/figure-html/atl_new_cases-1.png)<!-- -->

## New Deaths in Metro Atlanta


```
## `geom_smooth()` using method = 'loess' and formula 'y ~ x'
```

![](Metro_Atlanta-_COVID_files/figure-html/atl_new_deaths-1.png)<!-- -->


# Georgia

## New Cases


```
## `geom_smooth()` using method = 'loess' and formula 'y ~ x'
```

![](Metro_Atlanta-_COVID_files/figure-html/georgia_new_cases-1.png)<!-- -->

## New Deaths


```
## `geom_smooth()` using method = 'loess' and formula 'y ~ x'
```

![](Metro_Atlanta-_COVID_files/figure-html/georgia_new_deaths-1.png)<!-- -->


# United States

## New Cases


```
## `geom_smooth()` using method = 'loess' and formula 'y ~ x'
```

![](Metro_Atlanta-_COVID_files/figure-html/us_cases-1.png)<!-- -->

## New Deaths


```
## `geom_smooth()` using method = 'loess' and formula 'y ~ x'
```

![](Metro_Atlanta-_COVID_files/figure-html/us_deaths-1.png)<!-- -->

