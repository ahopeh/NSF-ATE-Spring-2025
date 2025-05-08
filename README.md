# NSF Grant Analysis - Spring 2025

[![Open in Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/aprilhope/nsf-grant-spring-2025)

Analysis of electric utility fees for NSF ATE grant (Spring 2025).


## Repository Structure
```
main
├── README.md                   # Project documentation
├── electricFeesApril.csv       # Raw fee data (2025 projections)
└── nsf-grant-spring-2025.ipynb # Jupyter Notebook analysis
```

## Quick Start
1. **View Analysis:**
   - Directly browse the notebook on GitHub:  
     [`nsf-grant-spring-2025.ipynb`](./nsf-grant-spring-2025.ipynb)

2. **Run Locally:**
   ```bash
   git clone https://github.com/your-username/repo-name.git
   cd repo-name
   pip install -r requirements.txt  # Create this if missing
   jupyter notebook nsf-grant-spring-2025.ipynb
   ```

3. **Kaggle Version:**
   - Click the "Open in Kaggle" badge above
   - Ensure dataset `electriccsv` is added to your Kaggle workspace

## Dataset
**File:** [`electricFeesApril.csv`](./electricFeesApril.csv)

| Column                     | Description                | Format      |
|---------------------------|----------------------------|-------------|
| Year                       | Fiscal year                | Integer     |
| Month                      | Calendar month             | String      |
| Purchased_Power_Adjustment | Energy cost adjustment     | USD (float) |
| Green_Infrastructure_Fee   | Sustainability initiative  | USD (float) |

## Requirements
Create `requirements.txt` with:
```txt
pandas>=1.5.3
matplotlib>=3.7.1
jupyter>=1.0.0
```

## Usage
```python
# Sample data loading (from repository root)
import pandas as pd
df = pd.read_csv('electricFeesApril.csv')  # Local path
```

## Contact
April Hope -  harrisah@hawaii.edu



