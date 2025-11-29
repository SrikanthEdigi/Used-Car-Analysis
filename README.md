# Used-Car-Analysis
## 📘 Project Description 
This project conducts a comprehensive EDA on a used-car dataset to identify the factors influencing vehicle pricing. It includes data cleaning, feature analysis, and visual exploration using Matplotlib and Seaborn, providing clear insights into how brand, year, fuel type, and usage impact resale value.

## Dataset Information
- File: car_data.csv
- Rows: 704
- Columns: 11

### Columns Description
| Column | Description |
|--------|-------------|
| Car_Name | Full name of the car |
| Brand | Manufacturer |
| Model | Model name |
| Year | Manufacturing year |
| Variant | Trim level |
| Fuel_Type | Petrol / Diesel / Electric |
| Kms_Driven | Kilometers driven |
| City | Location |
| Price | Selling price |
| Test_Drive_Availability | Home test drive availability |
| Unnamed: 0 | Index column |

## Data Cleaning
- Dropped index column
- Checked missing values
- Removed duplicates
- Corrected datatypes
- Detected outliers (boxplot & IQR)

## Univariate Analysis
Explored:
- Price distribution
- Fuel type counts
- Year-wise distribution

## Bivariate Analysis
Studied relationships:
- Price vs Kms Driven
- Price vs Brand
- Price vs Year
- Fuel Type vs Price

## Multivariate Analysis
Used:
- Pairplots
- Heatmaps
- Grouped aggregations

## Visualizations
Created:
- Bar charts
- Scatterplots
- Boxplots
- Heatmaps
- Histograms

## How to Run
Install packages:
```
pip install pandas numpy matplotlib seaborn
```

Run the notebook:
1. Open EDA Project.ipynb  
2. Ensure car_data.csv is in the same folder  
3. Run all cells

## Repository Structure
```
├── car_data.csv
├── EDA Project.ipynb
└── README.md
```

