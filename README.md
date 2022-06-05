
# King County House Price Prediction


**Authors**:<font color='Blue'> Aswathi Sasikumar </font>

## Overview

This project uses the King County House Sales dataset which has data about houses in King county like price,condition,grade,no of bedrooms,floors etc.This projects helps stakeholder,Real-estate agency to provide advice to homeowners about how home renovations might increase the estimated value of their homes, and by what amount.The regression model developed in the project predicts the price of the house and how certain parameters affect the price of the house.

## Business Problem

Real-estate agency needs to provide advice to homeowners on what factors can increase the estimated value of their homes.The regression model developed in the project predicts the price of the house and identifies the parameters that can affect the price of the house.

## Data

This project uses the King County House Sales dataset.It has 21597 data records

## Methods

Exploratory data analysis was used to analyse the data and to draw conclusions and multiple regression using OLS statsmodels was used to develop a model with price as dependent variable


## Results

The Findings of the analysis are detailed below:
Factors affecting price of a house are sqft_living,no of bedrooms and no of bathrooms.Model was developed using OLS statsmodels with price as dependent variable and sqft_living,bedrooms,bathrooms as independent variables.
![sqft](https://user-images.githubusercontent.com/103409242/172045708-7262dca2-958c-4a04-8035-b038585fabe1.png)

![corr](http![Screen Shot 2022-06-05 at 8 12 31 pm](https://user-images.githubusercontent.com/103409242/172045719-c5572be2-cd23-4803-af88-4aa5fbe953ae.png)
s://user-images.githubusercontent.com/103409242/172045710-3fa27271-de9a-4481-b3ef-0d49c8e0159d.png)

## Conclusions

Square footage, no of bedrooms and bathrooms are the best predictors of a house's price in King County. Homeowners who are interested in selling their homes at a higher price should focus on expanding square footage and improving the quality of construction.


## For More Information

Please review our full analysis in [our Jupyter Notebook](./dsc-phase1-project-template.ipynb) or our [presentation](./DS_Project_Presentation.pdf).

For any additional questions, please contact ** Aswathi Sasikumar at [kukkuaswathi@gmail.com](mailto:alison.kukkuaswathi@gmail.com)

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase1-project-template.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
