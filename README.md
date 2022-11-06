# MAM23 Data Visualisation - Group 11 Final Project

# Topic Idea 1: Happiness

![smiley](/images/smiley_cube.jpg)

## What is your topic?

**Cracking the code to human happiness**

<p align="center">
<i>The purpose of our life is to be happy</i>
~ Dalai Lama
</p>


## What issues or questions are you addressing?

Within our analyses and visualisations we want to answer the following research questions:
- Which countries are the happiest?
- Why are some countries happier than others?
- How (and why?) did happiness change over time for selected countries?
- What is the influence of specific events (e.g. covid) on happiness?


## What is the source of the data you will be using? 

As starting point we will be using the World Happiness Report for the years from 2015 to 2022.  The report is published by the Sustainable Development Solutions Network and powered by the Gallup World Poll data: https://worldhappiness.report/archive/. \
Since there is no single dataset and parameters have changed over the years, we will have to clean and merge single datasets.

Furthermore, additional datasets will be added in order to enhance the informative power of this project. These variables can include e.g. unemployment rate, government system type, crime rates, drug consumption, abortion rights and many more. One main source for this information will be the gapminder dataset: https://www.gapminder.org/data/.


## What statistical techniques do you think you may be using?

To estimate a potential happiness score of a country in a specific year, we will determine a multiple linear regression model with LASSO and k-fold cross-validation. This model will take into account the additional parameters - without using the country name itself as a categorical variable. 



# Topic Idea 2: Homicide

![killer](/images/homicide.jpg)

## What is your topic?

**Intentional Homicides across geographies, demographics, and time**

## What issues or questions are you addressing?

Within our analyses and visualisations we want to answer the following research questions:
- Which causes of death are most common?
- Which countries present the highest homicide rate vs the highest death rate by homicide cause?
- How did homicide rates evolve over time?
- What is the effect of gender, age, or relationship to killer on homicide rates?
- Can homicide rates be predicted by external parameters such as GDP?
- Are guns really a decisive factor when it comes to homicides?


## What is the source of the data you will be using? 

We will be using two main data-sources for as basis for this project.\
The first data-set will be an aggregation from several single datasets published by the Global Change Data Lab: https://ourworldindata.org/homicides#how-have-homicide-rates-changed-over-the-long-run-until-today .\
The second data-set is provided by the United Nations and can be accessed at: https://dataunodc.un.org/dp-intentional-homicide-victims.

Furthermore, additional datasets will be added in order to enhance the informative power of this project. These variables can include e.g. unemployment rate, government system type, GDP, drug consumption, and many more. One main source for this information will be the gapminder dataset: https://www.gapminder.org/data/.


## What statistical techniques do you think you may be using?

It will be a difficult task to predict homicide rates as the factors within each country are so peculiar. However, a multiple linear regression model with LASSO and k-fold cross-validation will be utilized to understand the predictory value that parameters such as continent, gdp, unemployment etc. have on the homicide rate. In addition we have planned to use bootstrapped comparison of means between single categories. 
