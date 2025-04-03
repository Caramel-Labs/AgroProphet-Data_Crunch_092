# AgroProphet by Caramel Labs

This is our submission for Data Crunch 2025, organized by CSE UOM.

The main notebook used for the final submission can be found in `Notebooks/DataCrunch_The_Final_Notebook.ipynb`. Other notebooks can be found in `Notebooks/experiments`.

## The Story Behind AgroProphet

After much debating, experimenting and sleepless nights, **Facebook Prophet** yielded the most performance - more than ARIMA, XGBoost and even various LSTM derivatives.

Neural Prophet might have been somewhat better still, but setting it up was a big hassle, with lots of dependency issues (mismatching `numpy` versions etc.), that we ultimately ended up with Prophet as our final solution, since it seemed to outperform pretty much every other solution we came up with.

## Setup

It is recommended to run this notebook in a Google Colab with Google Drive mounted and the CSV data files stored in a folder named `DataCrunch` in your Google Drive.

For local development, the following dependencies are required to be installed:

```sh
pip install numpy pandas scipy statsmodels matplotlib seaborn prophet pmdarima xgboost tqdm ipykernel jupyter
```

Make sure to remove / avoid running Colab-related code (e.g. mounting Google Drive) before running the notebook locally.

---

Made with ❤️ by Caramel Labs
