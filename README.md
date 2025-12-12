# first-data-app
Streamlit Time Series Explorer

This small Streamlit app displays a dataset, runs stationarity tests (ADF and KPSS), shows ACF and seasonality diagnostics (periodogram + decomposition), and lets the user download the data.

Quick start (Windows PowerShell):

1. Create and activate a virtual environment (optional but recommended):

```powershell
python -m venv .venv; .\.venv\Scripts\Activate.ps1
```

2. Install dependencies:

```powershell
pip install -r web_app\requirements.txt
```

3. Run the app:

```powershell
streamlit run web_app\app.py
```

Notes:
- By default the app will try to load `c:\\Users\\ABL\\Desktop\\PJME_hourly.csv`. You can upload a CSV instead.
- The app chooses the first numeric column for tests by default; you can select a different numeric column in the sidebar.
- If you want me to run a quick import check or attempt to run the app here, tell me and I will check for missing packages and run a small verification command.

