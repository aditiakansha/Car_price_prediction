# Car Price Prediction Project

This project predicts used car prices using a machine learning model built in Python and served through a Streamlit web app.

## Project structure

- `application/car_price_prediction_app.py` — Streamlit app
- `data/cars_dataset.csv` — dataset used for training and analysis
- `saved_models/` — trained model files
- `saved_scaling/` — scaler used for preprocessing
- `requirements.txt` — Python dependencies

## Quick start

1. Clone the repository

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
```

2. Create and activate a virtual environment

On Windows (PowerShell):

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

On macOS/Linux:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Run the app

```bash
streamlit run application/car_price_prediction_app.py
```

After the command starts, Streamlit will show a local URL such as:

```text
http://localhost:8501
```

Open that URL in your browser to use the app.

## Notes

- The app uses dataset and model files stored inside this project folder, so it works on any system after cloning the repo.
- If Streamlit is not installed after running the requirements command, install it manually:

```bash
pip install streamlit
```

## Requirements

The project dependencies are listed in `requirements.txt` and include Streamlit and the machine learning libraries needed for prediction.
