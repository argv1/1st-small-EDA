![logo](https://github.com/argv1/1st-small-EDA/blob/master/images/map.PNG)
## 1st-small-EDA: Real Estate King's County
======================

Running the Data Science Lifecycle by analysing real estate sells in the King County area

## Data Science Lifecycle

- 1 Business Understanding
    - What data do I reveived?
    - What could be achieved with this data?

- 2 Data Mining
    - Data set already provided
    - Column explanations not for every column
	  used [King County glosary](https://www.kingcounty.gov/depts/records-licensing/archives/research-guides/glossary.aspx)
 
- 3 Data Cleaning
    - Reformating variables
    - Dropping columns and rows due to lack of information or too many missing
 
- 4 Data Exploration
    - Spreading measures
    - Histograms
    - Correlation analyis
 
- 5 Feature Engineering
    - Year & Quarter the house was sold
    - Location by latitude * longitude
    - SQ difference between sq living and lot
    - Logarithm of price
    - Time between year build and sold
 
- 6 Predictive Modeling
    - Linear Regression
 
- 7 Data Visualization
    - Relation between price and grading
    - Location impact on price

## Summary:

- Cleaning is time consuming
- Lake View is very expensive
- There is a chance to buy a bargain.


## Outlook

To improve the prediction quality the following points could be done:
- The use of other regression models 
- Enrichment with external data


## Python Modules used:

Pandas / NumPy / Matplotlib / Seaborn / sklearn


## Files and Folders

- data/King_County_House_prices_dataset.csv provided data set
- data/column_names.md provided column explanations
- EDA.ipynb : jupyter notebook with Exploratory Data Analysis (EDA), python code, visualizations, further documentation and business case
- slides/King_County_EDA.pdf : slide deck visualising the findings (10min.)


## License

This code is licensed under the [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/). 
For more details, please take a look at the [LICENSE file](https://github.com/argv1/1st-small-EDA//blob/master/LICENSE).

