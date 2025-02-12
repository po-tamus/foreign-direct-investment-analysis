# Political Factors Influencing Foreign Direct Investment
## Goal
Determining the extent to which political factors influenced foreign direct investment in China and India over the past three decades.
## Setup
1. Set up environment: 
```bash
# Create virtual environment
python -m venv venv

# Activation
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Data has been collected and is stored in the `data` directory - execute the formatting files to format the data
	1. `fdi_formatting.ipynb`
	2. `gdp_formatting.ipynb`
	3. `political_factors_cleaning.ipynb`
5. This project stores and accesses data from a MySQL server - Install MySQL Server
6. Run `database_init.ipynb` in the `database_init` directory
7. Run Modeling Files in the `modeling` directory
	1. `economic_freedom_fdi_restrictiveness.ipynb`
	2. `fdi_time_series.ipynb`
	3. `governance_indicator_models.ipynb`
