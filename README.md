# VISUALIZATION DATASETS

Datasets for class and exercises

## WINE REVIEWS
- **Description:** Dataset containing wine reviews scraped from [WineEnthusiast](https://www.winemag.com/?s=&drink_type=wine) on November 22nd, 2017. 
- **Content:** CSV file containing 13 columns x ~130K rows
- **Columns:**
    - *country*: text, country where wine is produced
    - *description*: text, wine description
    - *designation*: text, vineyard within the winery where the grapes that made the wine are from
    - *points*: number, number of points WineEnthusiast rated the wine on a scale of 1-100 (they only post reviews for wines that score \>=80)
    - *cost*: number, cost for a bottle of the wine
    - *province*: text, province or state that the wine is from
    - *region_1*: text, wine growing area in a province or state (i.e. Napa)
    - *region_2*: text, sometimes there are more specific regions specified within a wine growing area (i.e. Rutherford inside the Napa Valley), but this value can sometimes be blank
    - *taster_name*: text, name of the taster
    - *taster_twitter_handle*: text, twitter handle of the taster
    - *title*: text, title of the wine review, which often contains the vintage if you're interested in extracting that feature
    - *variety*: text, type of grapes used to make the wine (i.e. Pinot Noir)
    - *winery*: text, winery that made the wine
- **URL:** https://www.kaggle.com/zynicide/wine-reviews


## BOSTON CRIME
- **Description:** Crime incident reports are provided by Boston Police Department (BPD) to document the initial details surrounding an incident to which BPD officers respond. This is a dataset containing records from the new crime incident report system, which includes a reduced set of fields focused on capturing the type of incident as well as when and where it occurred. The data is provided by Analyze Boston. Records begin in June 14, 2015 and continue to September 3, 2018. 
- **Content:** CSV file containing 17 columns x ~319K rows
- **Columns:**
    - *INCIDENT_NUMBER*: text
    - *OFFENSE_CODE*: number
    - *OFFENSE_CODE_GROUP*: text
    - *OFFENSE_DESCRIPTION*: text
    - *DISTRICT*: text
    - *REPORTING_AREA*: number
    - *SHOOTING*: text
    - *OCCURRED_ON_DATE*: datetime
    - *YEAR*: number
    - *MONTH*: number
    - *DAY_OF_WEEK*: text
    - *HOUR*: number
    - *UCR_PART*: text
    - *STREET*: text
    - *Lat*: number
    - *Long*: number
    - *Location*: text
- **URL:** https://www.kaggle.com/AnalyzeBoston/crimes-in-boston

## BOSTON POLICE DISTRICTS
- **Description:** City of Boston police districts. 
- **Content:** GeoJSON containing 12 features
- **URL:** https://data.boston.gov/dataset/police-districts

## TITANIC
- **Description:** The sinking of the Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone on board, resulting in the death of 1502 out of 2224 passengers and crew. While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.
- **Content:** CSV file containing 12 columns x 891 rows
- **Columns:**
    - *PassengerId*: number
    - *Survived*: number
    - *Pclass*: number
    - *Name*: text
    - *Sex*: text
    - *Age*: number
    - *SibSp*: number
    - *Parch*: number
    - *Ticket*: text
    - *Fare*: number
    - *Cabin*: text
    - *Embarked*: text
- **URL:** https://www.kaggle.com/datasets/yasserh/titanic-dataset

## COMPANY SALES
- **Description:** Profits over one month time of different products.
- **Content:** CSV file containing 9 columns x 12 rows
- **Columns:**
    - *month_number*: number
    - *facecream*: number
    - *facewash*: number
    - *toothpaste*: text
    - *bathingsoap*: text
    - *shampoo*: number
    - *moisturizer*: number
    - *total_units*: number
    - *total_profit*: text
- **URL:** https://www.kaggle.com/datasets/yasserh/titanic-dataset
