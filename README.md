# Data Manipulation
## Assignment: LEGO Project
### Name: Richard Lee

## Overview

In this assignment, you will load the various tables from the [Rebrickable](https://rebrickable.com/) website and perform analysis on the data.  Rebrickable is a fantastic website that is used to show you which LEGO sets you can build from the sets and parts you already own.  They will even show you which parts you are missing to complete the new set and suggest sets that you could purchase to get those parts.  

## Data

The data has been downloaded directly from their website and includes files for the tables shown in the schema above.  Your first task will be to go through the data and review the schema to understand how the tables all fit together.  There is no data dictionary that I am aware of, but you should be able to understand this data by reviewing the files and schema and visiting their [Download](https://rebrickable.com/downloads/) page and [API](https://rebrickable.com/api/) documentation. 

## Assignment

In this assignment, you will create a number of functions to complete certain tasks.  This is not needed if you were working on this project on your own, but since we want to see if you can select the data via Pandas/Numpy, we will use those functions in the automatic grading in CodeGrade.  Without this, students could try to look up the answers in the `csv` files instead of wrangling the data with Python/Pandas, which would defeat the purpose of this class.

In addition, we would strongly suggest that you merge data sets as appropriate for the given task.  For example, you might merge the `sets` and `themes` DataFrames to answer one question, and then merge `sets`, `inventories`, `inventory_minifigs`, and `minifigs` to answer another.  This will make your code much easier to write and will be key in working with data across multiple tables.  In fact, I was able to create each function with only one line of code because of the merging of certain data sets.  Also note that you may not use all the tables in this assignment.  This is also an important skill for a Data Scientist to know when to use data and what data is unnecessary.
