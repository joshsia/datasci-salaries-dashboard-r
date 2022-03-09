# datasci-salaries-dashboard-r

## About

A simple Dash-R app deployed on Heroku which shows the distribution of data science salaries for different countries. The dashboard can be found [here](https://dsci532-2022-ia2-joshsia.herokuapp.com/).

## Data

Data for this project was obtained from [Kaggle Data Scientists Salaries Around the World](https://www.kaggle.com/ikleiman/data-scientists-salaries-around-the-world/data). Specifically, the files `conversionRates.csv` and `multipleChoiceResponses.csv` are used in this project.

The data is processed using `src/data_cleaning.R` to mainly remove observations that do not have salary data, and to convert all salaries to USD.

## Description of app

The app has a single landing page which shows one plot. By default, the plot shows the distribution of data science salaries for all countries as a stacked histogram by formal education level. Two widgets are provided to specify the country to view data science salaries for, and to change how the histogram is stacked by.


Default page            |  `Canada` and `Coding Experience`
:-------------------------:|:-------------------------:
![default](https://github.com/joshsia/datasci-salaries-dashboard-r/blob/main/media/dashboard-1.png)  |  ![canada](https://github.com/joshsia/datasci-salaries-dashboard-r/blob/main/media/dashboard-2.png)
