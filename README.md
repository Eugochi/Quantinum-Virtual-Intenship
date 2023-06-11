![image](https://github.com/Eugochi/Quantinum-Virtual-Intenship/assets/123215066/d169e2cd-0d78-49da-af5f-ad9a9cef5cde)


# Quantium Data Analytics Virtual Internship

Task 1

## Installations

Libraries used in this projects

```
import pandas as pd
import numpy as np
import matplotlib
import matplotlib.pyplot as plt
import missingno as msno
import plotly.express as px
from IPython.display import HTML
import plotly.graph_objects as go
%matplotlib inline
import seaborn as sns
import datetime as dt
from plotnine import ggplot, aes, geom_point, geom_line
import scipy
from scipy.stats import ttest_ind
import scipy.stats as stats
import warnings
warnings.filterwarnings('ignore')
  
```
    
## Main goal for task 1
1. Creating and interpreting high level summaries of the data
2. Finding outliers and removing these (if applicable)
3. Data cleaning: Checking data formats and correcting (if applicable)

## Data Analysis on Customer Segments
The 4 main questions answered in data analysis were:

1. Who spends the most on chips (total sales), describing customers by lifestage and how premium their general purchasing behaviour is
2. How many customers are in each segment
3. How many chips are bought per customer by segment
4. What's the average chip price by customer segment



## Screenshots

![image](https://github.com/Eugochi/Quantinum-Virtual-Intenship/assets/123215066/0ef56ad5-51d5-4503-885a-fac84fa2625c)

![image](https://github.com/Eugochi/Quantinum-Virtual-Intenship/assets/123215066/8a1bc7f3-c817-4dc6-aae5-4ab50421dc5d)

![image](https://github.com/Eugochi/Quantinum-Virtual-Intenship/assets/123215066/48af04c8-45a9-4788-afab-42ea9c444d3d)

## CONCLUSION

After the analysis some insights were found that could be communicated to the category manager for informed decision on the nature of chips sales in the region. these includes the following:

It is seen that Sales have mainly been due to Budget - older families, Mainstream - young singles/couples (YSC), and Mainstream retirees shoppers.

We found that the high spend in chips for mainstream young singles/couples and retirees is due to there being more of them than other buyers.

Mainstream, midage and young singles and couples are also more likely to pay more per packet of chips.

From the lasts visualizations, we can also see that the Mainstream young singles and couples are more likely to to purchase the kettle chips than any other population and they mostly go for the 175g followed by the 150g pack size. When also compared with budget and premium midage and young singles and couples, we find out that the mainstream YSC result remains same.

This should be a great opportunity for the Category Manager to increase Kettle and small packs of chips in areas where Young singles and couple frequent and also improve sales of chips like Tyrells and Grain which has more consumption potentials among the YSC than other populations. This will increase visibility and further enhance impulse buying behaviour.



# Main Goal for Task 2
The client has selected store numbers 77, 86 and 88 as trial stores and want 
control stores to be established stores that are operational for the entire 
observation period.
We would want to match trial stores to control stores that are similar to the trial
store prior to the trial period of Feb 2019 in terms of :
- Monthly overall sales revenue
- Monthly number of customers
- Monthly number of transactions per customer


