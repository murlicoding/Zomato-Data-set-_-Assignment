The Zomato dataset contains information about 9551 restaurants and 21 columns covering various details such as restaurant name, country code, city, address, cuisines, average cost, ratings, votes, and service options. Only 9 entries are missing values in the “Cuisines” column; all other columns are complete.
Dataset Overview
	•	9551 records, 21 columnsattached_file:ffefaffa-1f28-42b8-abec-c1e092f17a0b.
	•	Key columns: Restaurant ID, Name, Country Code, City, Cuisines, Average Cost for two, Currency, Table booking, Online delivery, Price range, Ratings, Votes.
Column Insights
	•	Most columns are non-null except “Cuisines” (missing for 9 entries)attached_file:ffefaffa-1f28-42b8-abec-c1e092f17a0b.
	•	Numerical columns: Ratings, Votes, Price, Longitude, Latitude.
	•	Categorical columns: Cuisine type, Currency, Service options.
Data Analysis Steps
	•	Check and handle missing values (“Cuisines” only; very few missing).
	•	Explore numerical variables (e.g., ratings, price, votes).
	•	Explore categorical variables (e.g., cuisines, service delivery, table booking).
	•	Find relationships between features (e.g., how ratings relate to price or online delivery)attached_file:ffefaffa-1f28-42b8-abec-c1e092f17a0b.
Here is an improved summary after reading both your Zomato dataset and the country code files, offering a more powerful dataset structure and mapping for further analysis.

## Country Code Mapping

Both "Country-Code.xlsx" and "Country-Code-2.xlsx" contain the same mapping:
- 1: India
- 14: Australia
- 30: Brazil
- 37: Canada
- 94: Indonesia
- 148: New Zealand
- 162: Phillipines
- 166: Qatar
- 184: Singapore
- 189: South Africa
- 191: Sri Lanka
- 208: Turkey
- 214: UAE
- 215: United Kingdom
- 216: United States[attached_file:94edce1d-d086-438f-a493-f2ce1f17d92b][attached_file:dcaef8d0-8c29-486c-b5f3-6fb42387639a]

## Zomato Data Sample (First 20 Rows)

Below is an improved sample presentation of the restaurant 

| Restaurant Name                 | City               | Country         | Cuisines                      | Avg Cost | Currency      | Has Table Booking | Delivers Online | Rating | Rating Text | Votes |
|---------------------------------|--------------------|----------------|-------------------------------|----------|--------------|------------------|-----------------|--------|-------------|-------|
| Le Petit Souffle                | Makati City        | Phillipines    | French, Japanese, Desserts    | 1100     | Botswana Pula(P) | Yes           | No              | 4.8    | Excellent   | 314   |
| Izakaya Kikufuji                | Makati City        | Phillipines    | Japanese                      | 1200     | Botswana Pula(P) | Yes           | No              | 4.5    | Excellent   | 591   |
| Heat - Edsa Shangri-La          | Mandaluyong City   | Phillipines    | Seafood, Asian, Filipino, Indian | 4000   | Botswana Pula(P) | Yes           | No              | 4.4    | Very Good   | 270   |
| Ooma                            | Mandaluyong City   | Phillipines    | Japanese, Sushi               | 1500     | Botswana Pula(P) | No            | No              | 4.9    | Excellent   | 365   |
| Sambo Kojin                     | Mandaluyong City   | Phillipines    | Japanese, Korean              | 1500     | Botswana Pula(P) | Yes           | No              | 4.8    | Excellent   | 229   |
| Din Tai Fung                    | Mandaluyong City   | Phillipines    | Chinese                       | 1000     | Botswana Pula(P) | No            | No              | 4.4    | Very Good   | 336   |
| Buffet 101                      | Pasay City         | Phillipines    | Asian, European               | 2000     | Botswana Pula(P) | Yes           | No              | 4      | Very Good   | 520   |
| Vikings                         | Pasay City         | Phillipines    | Seafood, Filipino, Asian, European | 2000  | Botswana Pula(P) | Yes           | No              | 4.2    | Very Good   | 677   |
| Spiral - Sofitel Philippine Plaza| Pasay City        | Phillipines    | European, Asian, Indian       | 6000     | Botswana Pula(P) | Yes           | No              | 4.9    | Excellent   | 621   |
| Locavore                        | Pasig City         | Phillipines    | Filipino                      | 1100     | Botswana Pula(P) | Yes           | No              | 4.8    | Excellent   | 532   |
| ...                             | ...                | ...            | ...                           | ...      | ...            | ...            | ...             | ...    | ...         | ...   |

## How to Use This Combined Data for Analysis

- **Map 'Country Code' to Country** for insights by region or filtering by country[attached_file:94edce1d-d086-438f-a493-f2ce1f17d92b][attached_file:dcaef8d0-8c29-486c-b5f3-6fb42387639a].
- **Analyze categorical and numerical features** with cleaner country information.
- **Perform EDA**: Missing value handling, correlation, price and rating distribution, cuisine diversity by country/city, and service features.

If you want queries, visualizations, or specific exploratory tasks with these datasets (e.g., top cuisines by country, ratings vs. cost), just ask!

Sources
[1] Country-Code.xlsx https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/103447468/94edce1d-d086-438f-a493-f2ce1f17d92b/Country-Code.xlsx
[2] Country-Code-2.xlsx https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/103447468/dcaef8d0-8c29-486c-b5f3-6fb42387639a/Country-Code-2.xlsx
[3] zomato.csv https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/103447468/3f77ace6-424e-4769-a989-88fc4b41ee41/zomato.csv
