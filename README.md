# BankLoanPrediction
This repository has demo materials for building a scikit-learn model, deploying it, and visualizing it with a shiny dashboard.

---

## Load R.zip to your RStudio - Managing dependencies

1. Download the R.zip here.
2. In your RStudio environment click `Upload`  then select the R.zip

Now you are using the same package versions I used when developing the dashboard.


## Commands to run dashboard:

```r
# clone this repository to your RStudio
system("git clone https://github.com/gfilla/BankLoanPrediction.git")

# find the R markdown file and run
rmarkdown::run("BankLoanPrediction/dashboard/bankPredictionWML.Rmd")

```

## Challenges

1. Add new tab to the dashboard called `Data` with a view of the dataframe `testScores`
2. Replace the JSON output with visualization of your choice

---

### Hints:

1. Check out renderDataTable
2. Start by duplicating the viz in the demo and check out this [Plotly book](https://plotly-book.cpsievert.me/) to help find interesting plots
