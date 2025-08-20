# BRASMOD

This repository contains the files and data necessary to run the BRASMOD microsimulation model. The model folder (`BRASMOD_v1.0`) follows the EUROMOD folder structure, with the following folders:

| ***Folder***| ***Description*** |
|-----|-----|
| `EM3Translation/XMLParam` |Translations of the XML files for the EUROMOD software|
| `Input` |Microdata input files (.txt) used to run the model|
| `Output` |Microdata output files (.txt) with the model results|
| `XMLParam` |XML files with the model and general project files|

The `Database setup` folder contains the original microdata files and R code necessary to build the microdata input files for the model, with the following structure:

| ***Folder***| ***Description*** |
|-----|-----|
| `Expenditure imputation` |Code and output results for statistical survey matching between POF and PNAD (dormant)|
| `Old PNAD data` |.RDS microdata for PNAD (2008-2015)|
| `POF data` |.RDS microdata for POF (2008-2009 and 2017-2018), along with translators and crosswalks|
| `Database setup` files |R code used to build the microdata input files (.txt) in the `Input` folder above|

The `assets/reports` folder stores the Country Report that accompanies the model. 

The `docs` folder just sets up the project website. 

**You can access the project website [here](https://brasmod.github.io/brasmod_main/).** 
