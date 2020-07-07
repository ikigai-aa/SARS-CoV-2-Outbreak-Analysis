# SARS-CoV-2-Outbreak-Analysis :india:

[![](https://i.imgur.com/5gj4USj.png)](https://github.com/ikigai-aa/SARS-CoV-2-Outbreak-Analysis/blob/master/a-page-001.jpg)

## Table of Content
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Technical Aspect](#technical-aspect)
  * [Prerequisites](#Prerequisites)
  * [To Do](#to-do)
  * [Bug / Feature Request](#bug---feature-request)
  * [Technologies Used](#technologies-used)
  * [License](#license)
  * [Data Sources](#data-sources)
 
 ## Overview

This is a simple IPython notebook in which there is performed Exploratory Data analysis on various datasets, Forecasting and Machine Learning implementation to study the COVID-19 outbreak, impact and spread using model evaluation.Extraction of important factors that impact transmission rate like temperature, humidity, population, and sun-hours with feature engineering after modeling is done at the later half of the notebook.

## Motivation
Beneficial to concerned client(s) desiring to have a detailed analysis of the present outbreak to have essence of present situation in order to discover and analyze the trend, behavior, responses to various factors affecting the market and invent , strategize precautionary measures for any future pandemic like this.

## Technical Aspect
This project is divided into some sections like:

1. To study SARS-CoV-2 outbreak with the help of some basic visualizations’ techniques.
2. To Perform predictions and Time Series forecasting in order to study the impact and spread of the SARS-CoV-2 in coming days.
3. To study some important factors that impact transmission rate of SARS-CoV-2 like Air Transmission, Relative humidity., Temperature.
4. To study the responses of countries to SARS-CoV-2 i.e. to classify the changes in the number of infections in different countries, hoping to find out the factors that affect  the country's ability to respond to it.
5. To have a sensible study to classify the trend of the number of infected people under the influence of different factors, and then modify the policy according to the trend of the expected number of infected people.
6. To analyze Growth Factor & Inflection.
7. To have an Exploratory Data analysis, Forecasting and implementing the Machine Learning Models wherever needed.

## Prerequisities
The Code is written in Python 3.7. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```
```bash
cmdstanpy==0.4.0
convertdate==2.2.1
cycler==0.10.0
Cython==0.29.20
ephem==3.7.7.1
holidays==0.10.2
joblib==0.16.0
kiwisolver==1.2.0
korean-lunar-calendar==0.2.1
LunarCalendar==0.0.9
matplotlib==3.2.2
numpy==1.19.0
pandas==1.0.5
patsy==0.5.1
plotly==4.8.2
PyMeeus==0.3.7
pyparsing==2.4.7
pystan==2.19.1.1
python-dateutil==2.8.1
pytz==2020.1
retrying==1.3.3
scikit-learn==0.23.1
scipy==1.5.1
seaborn==0.10.1
setuptools-git==1.2
six==1.15.0
sklearn==0.0
statsmodels==0.11.1
threadpoolctl==2.1.0

```

## To Do
1. Convert the app to run without any internet connection, i.e. __PWA__.
2. Add a better vizualization chart to display the predictions.
3. Deploying this project to a web app using heroku. 

## Bug / Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/ikigai-aa/SARS-CoV-2-Outbreak-Analysis/issues/new) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/ikigai-aa/SARS-CoV-2-Outbreak-Analysis/issues/new). Please include sample queries and their corresponding results.

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)


## License
[![Apache license](https://img.shields.io/badge/license-apache-blue?style=for-the-badge&logo=appveyor)](http://www.apache.org/licenses/LICENSE-2.0e)

MIT License

Copyright (c) 2020 Ashish Agarwal

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Data Sources 

Articles:
1. https://www.ijidonline.com/action/showPdf?pii=S1201-9712%2820%2930123-5
2. https://www.sciencedirect.com/science/article/pii/S1201971220301235
3. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7098030/
4. https://www.ijidonline.com/article/S1201-9712(20)30123-5/fulltext


Datasets:
1. https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset
2. https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data
3. https://www.kaggle.com/imdevskp/corona-virus-report
4. https://www.kaggle.com/parulpandey/coronavirus-cases-in-india
5. https://worldpopulationreview.com/countries/most-visited-countries/


