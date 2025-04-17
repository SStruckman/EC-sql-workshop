
# SQL workshop
Built for EC Workshop April 2025  
Soren Struckman

## Getting started
This workshop uses a few different files and software packages at different times. The idea is that we can get a feel for a couple different ways we might work with databases. You may either (a) work on the [sql-workshop-TEMPLATE.Rmd](https://github.com/sstruckman/EC-sql-workshop/blob/main/sql-workshop-TEMPLATE.Rmd), which leaves space for participants to type code with instruction, or (b) follow along along in the [sql-workshop-KEY.Rmd](https://github.com/sstruckman/EC-sql-workshop/blob/main/sql-workshop-KEY.Rmd), which has all of the information and code we will be working with. Download the [sql-workshop-KEY.html](https://github.com/sstruckman/EC-sql-workshop/blob/main/sql-workshop-KEY.html) for a knitted (and much easier to read) version of the KEY. The first portion of the workshop will be interactive within SQLite Studio, so examples are not worked through in the KEY. 

## Outline
1. What and why of databases and SQL
2. Exploring SQLite Studio
3. Constructing some useful queries
4. Working with databases using SQL in R. 

## Data source
All [dragon data](https://cran.r-project.org/web/packages/DALEX/DALEX.pdf) are modified from the `DALEX` package. (Some other fake data are added and Wrapped up into a `.db` file for our convenience). 


## Software
This workshop requires some software that you might already have installed, and some you might not. Please make sure you have the following running on your machine before the workshop begins.

1. **SQLite Studio** is a desktop application for opening, viewing, and working with SQL databases (actually the "SQLite"" variant, but NBD for us). Download and install the newest release for your operating system [here](https://github.com/pawelsalawa/sqlitestudio/releases).
2. **R** and **RStudio** are common tools for data science programming. If you don't have them already, follow this [guide](https://posit.co/download/rstudio-desktop/).
3. For the R portion of the workshop, we will need the `DBI` and `RSQLite` packages, which can be installed by running `install.packages(c("DBI","RSQLite"))` in R.

