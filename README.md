# MAM23 Data Visualisation - Group 11 Final Project

![smiley](/images/smiley_cube.jpg)

## What is your topic?

**Cracking the code to human happiness :)**

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

To infer which parameters are likely to explain a specific happiness score (other than the country itself), we will determine a linear regression model with LASSO and k-fold cross-validation.
