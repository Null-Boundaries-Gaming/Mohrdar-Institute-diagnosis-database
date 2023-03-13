# Mohrdar-Institute-diagnosis-database

## Table of Content 

  - [Table of Content](#table-of-content)
  - [Introduction](#introduction)
  - [Format](#format)


## Introduction
The databases for the diagnosis part of the program.


## Format 

The format is a csv file, to import into postgreSQL. It contains following format:  
```Shell
ICD10_symptom1|symptom2|_lab1|lab2|
```
**ICD10 codes must have ` - ` between the code and the description  
Lab values have to start with `LOW - Name` or `HIGH - Name`**