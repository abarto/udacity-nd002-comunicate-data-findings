# Project - Communicate Data Findings - Prosper Load Data Exploration
## by Agustin Barto

## Table of Contents

* [Introduction](#introduction)
* [Dataset](#dataset)
* [Summary of Findings](#problems)
* [Key Insights for Presentation](#key-insights)
* [Conclusions](#conclusions)

## Introduction<a class="anchor" id="introduction"></a>

This repository contains my submission to the "Communicate Data Findings" project of the Udacity's Data Analyst Nanodegree program. These are the contents of the repository:

* README.md: This file.
* [Part_I_exploration.ipynb](Part_I_exploration.ipynb): Jupyter notebook containing the first part of the project where we perform the data wranging and exploratory analysis.
* [Part_II_slide_deck.ipynb](Part_II_slide_deck.ipynb): Jupyter notebook containing the second part of the project where we present the findings of the first part.
* [prosperLoanData.csv.zip](prosperLoanData.csv.zip): Compressed data set.
* [requirements.txt](requirements.txt): PyPI requirements file containing the dependencies needed to run the code of the notebooks.

## Dataset<a class="anchor" id="dataset"></a>

I've chosen the "Loan Data from Prosper" dataset as it strikes a good balance between size, complexity and richness. It has a lot of variables to chose from, both numerical and categorical and enough samples to provided meaningful results.

This data set contains information about 113937 loans from [Prosper](https://www.prosper.com/) with 81 variables for each of them.

## Summary of Findings<a class="anchor" id="findings"></a>

* There was a dip in number of loans on 2009
* Most loans are taken at the end of the year
* BorrowerRate, BorrowerAPR and LenderYield have similar multi-modal distributions
* Most loans are taken for debt consolidation
* The vast majority of loans have 36 month terms
* Half the borrowers are home owners
* Loans are taken mostly on "round" amounts
* BorrowerRage and BorrowerRate are highly correlated, but there's another variable that's grouping the loans
* Higher credit grades (for both variables) lead to lower borrower rates
* At least for deals after 2009, the term is a factor that increases the APR over the rate

## Key Insights for Presentation<a class="anchor" id="key-insights"></a>

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.

## Conclusions<a class="anchor" id="presentation"></a>
