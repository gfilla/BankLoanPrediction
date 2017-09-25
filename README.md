# BankLoanPrediction
This repository has demo materials for building a scikit-learn model, deploying it, and visualizing it with a shiny dashboard.

---

## Commands to run dashboard:

```r
system("git clone https://github.com/gfilla/BankLoanPrediction.git")

source("BankLoanPrediction/dashboard/requirements.r")

rmarkdown::run("BankLoanPrediction/dashboard/bankPredictionWML.Rmd")

```
