DATA REPORT FOR MTN Cote d'Ivoire

BUSINESS UNDERSTANDING
Business Overview
Telecommunications companies improve their technology infrastructure so that they can provide their customers with easy access to information and service regardless of their location or time.
MTN Cote d'Ivoire has a good coverage of their network across the country but still most of the cities lag behind in their access to good network coverage.

Business Objective
The main objective of this report is to come up with a good way to go about the upgrade of MTN Cote d'Ivoire technology infrastructure within the cities.

BUsiness Criteria
To compile the list of cities that should be prioritized in the upgrade depending on the type of product they use and how often they use it.

Assessing the Situation
Resource Inventory
Datasets:
cells_geo_description.xlsx [Link]
cells_geo.csv [Link]
CDR_description.xlsx [Link]
CDR 20120507 [http://bit.ly/TelecomDataset1
CDR 20120508 [http://bit.ly/TelecomDataset2]
CDR 20120509 [http://bit.ly/TelecomDataset3]

Software( Github, Google Collaboratory, SQLite)
Assumptions
The data provided is correct and up to date
Constraints
There are no constraints

Data Mining Goals
Our data Mining goal are :
Which ones were the most used city for the three days
Which cities were the most used during business and home hours
Most used city for the three days
Product list used per city

Data Mining Criteria
Our success criteria will be measured by the following criteria:
Upgrade the infrastructure of the city on the type of product they use.
2. Data Understanding
Data UNderstanding Overview
We are using the availed dataset by the company. These datasets are;
Telecommunication dataset - this is the dataset that has the product used and time and date the product is used.
Geographical dataset - this dataset shows the cities that the products are used.

3. Data Preparation
This are the steps followed in the data preparation process ;
Data loading  - loaded the data set in the google colaboratory from .Csv and .xlsx to a dataframe.
Data Cleaning - some of the column heads on the dataset we misspelled so l renames all the columns and also converted the column heads to uppercase.
Merging of the dataframes - l first merged all the three dataset from the Telcom dataset and create one dataset . After l merged the one dataset of the Telcom dataset with the Geo dataset to create the final dataframe.

Analysis
During our analysis, we were able to single out the following states;
Each city and the product they use

PRODUCT  VILLES
Voice    ABENGOUROU         96
         ABOBO            1966
         ABOISSO            42
         ABOISSO COMOE      12
         ABONGOUA            3
                          ...
sms      ZAIBO              15
         ZAROKO              3
         ZIKISSO            24
         ZOUKOUGBEU          6
         ZUENOULA           54
Name: VALUE, Length: 601, dtype: int64
The above analysis was done using SQLite. The full analysis can be found in the following notebook.[Link]

Recommendations
From our analysis l would recommend the MTN company to upgrade the infrastructure in each city while prioritizing the necessary infrastructure that  is needed for the product used the most per city.
