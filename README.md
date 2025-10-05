# BMW-analysis
# BMW Car Sales EDA

## Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on a BMW car sales dataset. The goal is to understand sales trends, pricing, mileage, engine sizes, and other key factors affecting BMW car sales. This analysis includes statistical summaries, visualizations, and correlations between features.

## Dataset Description
The dataset contains the following columns:

| Column Name           | Description                                         |
|-----------------------|-----------------------------------------------------|
| Model                 | BMW car model                                      |
| Year                  | Car model year                                     |
| Region                | Region of sale                                     |
| Color                 | Car color                                         |
| Fuel_Type             | Type of fuel (Petrol, Diesel, Electric, etc.)    |
| Transmission          | Type of transmission (Automatic/Manual)          |
| Engine_Size_L         | Engine size in liters                             |
| Mileage_KM            | Distance traveled by car in kilometers           |
| Price_USD             | Sale price of the car in USD                      |
| Sales_Volume          | Number of units sold                              |
| Sales_Classification  | Category of sales (e.g., High, Medium, Low)      |

## Libraries Used
- `pandas` – Data manipulation and analysis  
- `numpy` – Numerical computations  
- `matplotlib` – Data visualization  
- `seaborn` – Advanced visualization  

## Steps Performed

### 1. Data Loading
- The dataset is loaded using `pandas.read_csv()`.
- Basic inspection using `.head()`, `.info()`, `.describe()`.

### 2. Data Cleaning
- Removed duplicate rows using `drop_duplicates()`.
- Handled missing values where necessary.
- Ensured correct data types for each column.

### 3. Feature Engineering
- Calculated `Car_Age` (if applicable) using `Year`.
- Created additional columns for better insights if needed.

### 4. Statistical Analysis
- **Mean, Variance, Mode** calculated for numerical columns.
- **Skewness** computed to understand data distribution.
- **Correlation** analyzed to see relationships between numerical features.

### 5. Data Visualization
- **Histograms**  <img width="859" height="547" alt="image" src="https://github.com/user-attachments/assets/2dd67ddb-6c4b-4bdc-ae4d-a2033a927abe" />

- **Boxplots**  <img width="721" height="509" alt="image" src="https://github.com/user-attachments/assets/0e171ba3-ab52-4c27-becd-56f88113fc60" />

- **Correlation** <img width="599" height="418" alt="image" src="https://github.com/user-attachments/assets/7fc23db8-f14f-4e0a-99a1-7a622407fa52" />
  

## Key Insights
- Price distribution is skewed (right or left depending on the dataset).  
- Mileage and engine size show correlations with price.  
- Certain regions or fuel types may have higher sales volume.  
- Boxplots reveal potential outliers in price and mileage.  

## Conclusion

This EDA provides a clear understanding of BMW car sales data, helping to identify trends, key patterns, and relationships between numerical and categorical features. The analysis can further support pricing strategies, market analysis, and predictive modeling.
