# BankLoanPrediction
This repository has demo materials for building a scikit-learn model, deploying it, and visualizing it with a shiny dashboard.

---

## Load R.zip to your RStudio - Managing dependencies

1. [Download the R.zip here](https://ibm.box.com/shared/static/fd8vgznfuv3x6rrx65vnxh4sj2chd7la.zip).
2. In your RStudio environment click `Upload`  then select the R.zip
<img src="https://github.com/gfilla/BankLoanPrediction/blob/master/img/upload.png" width= 350>

Note: This will take some time to complete

3. Click yes to the prompt about overwriting (unless you have R packages in your R directory you need to keep)

<img src="https://github.com/gfilla/BankLoanPrediction/blob/master/img/yes.png" width= 350>

4. Restart R!
<img src="https://github.com/gfilla/BankLoanPrediction/blob/master/img/restart.png" width= 300>


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
