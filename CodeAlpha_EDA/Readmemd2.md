# CodeAlpha Task 2: Exploratory Data Analysis (EDA) - Titanic Dataset

## Dataset
Titanic passenger data from Kaggle (891 passengers, 12 features)

## Questions I Asked
1. What was the overall survival rate?
2. Did gender affect survival?
3. Did passenger class affect survival?
4. How did age impact survival?
5. What factors correlate with survival?

## Steps Performed
1. Loaded Titanic dataset from GitHub
2. Checked for missing values (Age, Cabin, Embarked)
3. Handled missing data:
   - Filled Age with median
   - Filled Embarked with mode
   - Dropped Cabin (too many missing)
4. Created visualizations:
   - Bar charts for survival by gender/class
   - Histograms for age/fare distribution
   - Correlation heatmap
   - Boxplots for outliers
5. Calculated survival statistics

## Key Findings
| Factor | Finding |
|--------|---------|
| Overall Survival | 38.4% of passengers survived |
| Gender | Women: 74% survived, Men: 19% survived |
| Class | 1st: 63%, 2nd: 47%, 3rd: 24% |
| Age | Children had higher survival rate |
| Fare | Higher fare = better survival chance |

## Visualizations Created
- Survival rate by gender
- Survival rate by passenger class  
- Age distribution of survivors vs non-survivors
- Correlation heatmap
- Fare distribution by class

## How to Run
1. Open Google Colab
2. Run all cells in order
3. No data download needed (loads from web)

## Files
- `eda_titanic.ipynb` - Complete analysis notebook
- `titanic_cleaned.csv` - Cleaned dataset (after handling missing values)

## Author
[D.V.NARASIMHA]
