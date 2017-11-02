# Bias in Data

## Goal of the Project
The goal of this analysis is to explore the definition of 'bias' through data on Wikipedia articles on political from different countries. 

## License and Terms
[MIT License](https://opensource.org/licenses/MIT)

## Prerequire Package 
- numpy

- pandas

- request

- csv

##  Data Scource

**Page data:** The wikipedia dataset can be found on [Figshare](https://figshare.com/articles/Untitled_Item/5513449).

**Population Mid 2015 data:** The population data is on the [Population Research Bureau website](http://www.prb.org/DataFinder/Topic/Rankings.aspx?ind=14). 

## Relevant API

**ORES:**  a Wikimedia API endpoint for a machine learning system [ORES ("Objective Revision Evaluation Service")](https://ores.wikimedia.org/v3/#!/scoring/get_v3_scores_context_revid_model).

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


There will four table to show:

- 10 highest-ranked countries in terms of number of politician articles as a proportion of country population
- 10 lowest-ranked countries in terms of number of politician articles as a proportion of country population
- 10 highest-ranked countries in terms of number of GA and FA-quality articles as a proportion of all articles about politicians from that country
- 10 lowest-ranked countries in terms of number of GA and FA-quality articles as a proportion of all articles about politicians from that country


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



