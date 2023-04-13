# Indian-Startup-Ecosystem
# Indian-Startup-Ecosystem
Welcome to team Quebec's new Kernel
The Kernel objective is to analyse and try to understand some fundig patterns in Indians Startup.

Some informations about dataset below

The team is interested in appraising indian startup ecosystem. Team Quebec was interested in knowing what type of startups are getting funded in the last few years? We also wanted to know who are the important investors? Wanted to know the hot fields that get a lot of funding these days? This dataset is a chance to explore the Indian start up scene. Deep dive into funding data and derive insights into the future!

## Content
In this project, team Quebec is going to analyse funding received by start-ups in India from 2018 to 2021..

Column names and description:

Company/Brand: Name of the company/start-up

Founded: Year start-up was founded

Sector: Sector of service

What it does: Description about Company

Founders: Founders of the Company

Investor: Investors

Amount($): Raised fund

Stage: Round of funding reached

## Methodology
We used the CRISP-DM methdology to answer analyse the dataset.
The model has six essential steps, including: 
1. Business Understanding- What does the business need?
2. Data Understanding - What data do we need? Is it clean?
3. Data Preparation - How do we organize the data for modelling?
4. Modelling - What modelling techniques should we Apply?
5. Evaluation - Which model best meets the business objectives?
6. Deployment - How do stakeholders access the results?

## Research Questions

1. What are the top 10 start-ups that have received the most funding?
2.What are the top 5 cities that have received the most funding?
3. Does the level of funding in each sector increase each year?
4. Who are the major investors (top 10) in the Indian ecosystem?
5. Which investors (top 5) invested the most money in India?
6. What are the top 5 sectors that receive the most funding ?
7. What are the top 5 Stages that Receive the Most Funding?

## Hypothesis
H0: There is no significant difference between year and average funding.
H1: There is significant difference between year and average funding.

## Import the following Libraries 

import numpy as np
import pandas as pd
from matplotlib import pyplot as plt
import seaborn as sns
import scipy.stats as stats
import statistics as stat
from summarytools import dfSummary
from decimal import Decimal

import warnings
warnings.filterwarnings('ignore')

# Other packages
import os
import re
#display all columns and rows 
pd.set_option('display.max_columns', None)
pd.set_option('display.max_rows', None)
from sklearn.impute import SimpleImputer