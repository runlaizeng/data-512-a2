# Bias in Data

## Goal of the Project
The goal of this analysis is to explore the definition of 'bias' through data on Wikipedia articles on political from different countries. 

## License and Terms
[MIT License](https://opensource.org/licenses/MIT)


##  Data Scource

**Page data:**The wikipedia dataset can be found on [Figshare](https://figshare.com/articles/Untitled_Item/5513449).

**Population Mid 2015 data:**The population data is on the [Population Research Bureau website](http://www.prb.org/DataFinder/Topic/Rankings.aspx?ind=14). 

## Relevant API

**ORES:**  a Wikimedia API endpoint for a machine learning system[ORES ("Objective Revision Evaluation Service")](https://ores.wikimedia.org/v3/#!/scoring/get_v3_scores_context_revid_model).

## Final Data File

Final data stores in folder```final_data``` called```final.csv```.

Values shown as follows:

|  Column |
|---|
| country  |
|  article_name|
|  revision_id |
|  article_quality|
|  population |

## Data Process and Analysis

Prerequiste Packages:

- requests

- json 

- csv

- pandas

- numpy


There will be visualizations to show:

1. the countries with the greatest and least coverage of politicians on Wikipedia compared to their population.

2. the countries with the highest and lowest proportion of high quality articles about politicians.

```a2-bias-in-data.ipynb``` under ```scr``` folder contains all code and information of data processing and analysis.

## Directory Structure

```
data-512-a2 (master)
|
|     License
|     README.md
|	    a2-bias-in-data.ipynb
|----- raw_data
|     | 
|     |      page_data.csv
|     |      Population Mid-2015.csv
|     | 
|----- final_data
|     |      
|     |      final.csv
|     | 

```



