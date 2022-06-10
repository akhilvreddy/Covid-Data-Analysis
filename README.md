# Coronavirus Data Analysis (Winter 2022)

## Brief Description
Project based in R which deals with covid data analysis. The goal of this project is to show correlation between the Covid19 booster shot to the quick end of the Winter 2022 (Dec 2021 - Jan 2022) wave. Used excel to sort and sift the data and used R in order to analyze the data.

<p align="center">
  <img 
    width="428.4"
    height="170"
    src="https://github.com/akhilvreddy/CovidDataAnalysis/blob/main/CovidProject/uscovidgraph.png"
  >
  <img 
    width="428.4"
    height="170"
    src="https://github.com/akhilvreddy/CovidDataAnalysis/blob/main/CovidProject/uscoviddeathgraph.png"
  >
</p>

> The blue graph represents the overall Coronavirus cases in the US. As you can see, there is a large peak around Winter 2022 and that is what we are doing our analysis on. 

> The gray graph represents the deaths chart due to Coronavirus cases in the US. As you can notice, though the cases were way higher in Winter 2022 than any other wave, deaths were not as high. We search for the reasoning of this in our project.

## Abstract
A lot of people doubted the efficacy of the covid booster shot when it first was introduced (around December 2021) due to the on-going wave at the time due to the omicron variant. The goal of this project is to prove whether the booster shot did help people from being infected less and reducing deaths. If the null hypothesis comes back as false, we aim to model what would happen with no vaccine booster at all. The bulk of this project was done in R, with some parts requiring other software. 

## Setup 
For this project the data we used was from the New Jersey Department of Health. It was lumped together in a large csv file. I tailored this to the data we need in a new csv file, titled __. I then put this file into R studio and did the analysis.

There were some data points that were complete outliers and I was sure they were going to skew the data so I wanted to throw them out. 


## Getting Started
Having the data in R studio, we started by making basic statistical plots in order to see if our data was normal. I also wanted to throw out some outliers (on both sides) to make the data better suited for analysis. 


### Plots
