# Task 1: Web Scraping - Titanic Data

## What I Did
- Loaded Titanic passenger data from a public source
- Saved it as a CSV file
- Downloaded it to my computer

## Results
- **Total records:** 891 passengers
- **Columns:** 12 (Name, Age, Ticket Class, Survival, etc.)
- **File size:** ~60 KB

## Code Used
```python
import pandas as pd
from google.colab import files

url = "https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv"
data = pd.read_csv(url)
data.to_csv('titanic_data.csv', index=False)
files.download('titanic_data.csv')