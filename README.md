# Australia Primary Education vs GDP (2001–2020)

This project explores the relationship between primary education enrollment and GDP per capita in Australia over a 20-year period (2001–2020). The dataset was cleaned and merged from two sources: United Nations education statistics and World Bank economic indicators.

##Files Included

- `australia_edu_gdp.csv`: Cleaned dataset containing year-wise enrollment and GDP data.
- `australia_edu_gdp.db`: SQLite database containing the same dataset for SQL-based analysis.
- `data_description.json`: JSON file describing each column in the dataset (name, type, and meaning).
- `Australia_Wrangling_Project.html`: Jupyter notebook export (HTML) showing data wrangling steps.

## 🔍 Columns Explained

| Column Name         | Data Type | Description |
|---------------------|-----------|-------------|
| `Year`              | Integer   | Calendar year (2001–2020) |
| `Primary Enrollment`| Float     | Number of students enrolled in primary education |
| `GDP per Capita`    | Float     | Gross Domestic Product per person (USD) |

##Tools Used

- Python (Pandas, SQLite3)
- Jupyter Notebook
- World Bank and UN datasets
- Visual Studio Code

##Objective

To investigate whether there's a trend between rising GDP per capita and increased primary school enrollment in Australia.

##Contact

Created for academic purposes.
