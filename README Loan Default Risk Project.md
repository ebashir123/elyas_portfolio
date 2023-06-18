# Data Analysis Project: Loan Default Risk Analysis

Welcome to my data analysis project showcasing an analysis of **loan data** from banks that explores the various factors that may lead to increased default rates on loans.

## Project Description
In this project, I analyzed bank loan data in an effort to address the factors that lead to increased default rates, so as to mitigate any further risks and provide these financial companies with better insights on how to address several factors regarding their consumers. This includes summary tables and statistical analysis on variables, as well as data visualization via **bar charts**, **density histograms**, and **boxplots**. Additionally, models such as **logistic regression**, linear discriminant analysis (**LDA**), and **random forests** were implemented to assess the data.

**NOTE: You must run the file in order to see the tables/graphs/models**

## How to Run
To view and interact with the visualizations, please follow these steps:

1. **Clone or Download**: Clone this repository to your local machine or download the project files.

2. **Install R and R Studio**: Ensure you have R and R Studio installed on your machine.

3. **Open the R Script**: Open the R script file (`Loan Default Rate Portfolio Project Exploratory Data Analysis+.Rmd`) using R Studio.

4. **Install the 'loan_data.rds' file in the repository.**

5. **Install Required Packages**: If any required packages are not already installed, use the `install.packages()` function to install them. Here are the required packages for this project:

```R
library(tidyverse)
library(tidymodels)
library(vip)
library(ggplot2)
library(rpart.plot)
library(ranger)
library(parsnip)
library(discrim)
