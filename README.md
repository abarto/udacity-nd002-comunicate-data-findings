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
* [Part_I_exploration.html](Part_I_exploration.html): HTML export of ``Part_I_exploration.ipynb``.
* [Part_I_exploration.pdf](Part_I_exploration.pdf): PDF printout of ``Part_I_exploration.html``.
* [Part_II_slide_deck.ipynb](Part_II_slide_deck.ipynb): Jupyter notebook containing the second part of the project where we present the findings of the first part.
* [Part_II_slide_deck.slides.html](Part_II_slide_deck.slides.html): Generated slides by converting ``Part_II_slide_deck.ipynb``.
* [prosperLoanData.csv.zip](prosperLoanData.csv.zip): Compressed data set.
* [prosper_load_data_clean.pickle](prosper_load_data_clean.pickle): Cleaned data set.
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
* BorrowerAPR and BorrowerRate are highly correlated, but there's another variable that's grouping the loans
* Higher credit grades (for both variables) lead to lower borrower rates
* At least for deals after 2009, the term is a factor that increases the APR over the rate

## Key Insights for Presentation<a class="anchor" id="key-insights"></a>

Mot of the exploration was geared towards finding the variables that influence ``BorrowerAPR``. While analysing some of these variables we did gain some insight about their structure and distribution. Sadly the specifics about the dataset, in particular the  2009 split, makes it easier to anser global hypothesis, but in the and we did manage to found at least one variable that had a measurable effect on the ``BorrowerAPR``.

## Conclusions<a class="anchor" id="presentation"></a>

* The subject matter is quite complex. The financial world (and loans in particular) are notoriously obscure when it comes to the modelling. Exploring the details behind all the variables was beyond the scope of this project.
* Some variables, like the credit grades, split the dataset in two, so this limited global explorations and it's an indicator that perhaps the rest of the variables should be segmented as well.
* All the information is mostly about the loans, and not so much about the borrowers. Some information, like the age, is a factor that can affect some of the variables.
