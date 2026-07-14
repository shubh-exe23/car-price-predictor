# Car Price Predictor

This project is a machine learning-based car price prediction tool that estimates the selling price of a used car based on its specifications and market trends. It uses a **Random Forest Regressor** trained on real-world data from CarDekho, with an interactive interface built using `ipywidgets`.

## Features

- Predicts selling price based on:
  - Year of manufacture (converted to car age)
  - Kilometers driven
  - Fuel type
  - Transmission type
  - Seller type
  - Ownership history
  - Car model
- Input validation — checks that the selected combination (model + fuel + transmission + seller + owner) actually exists in the dataset before predicting, and suggests valid alternatives if not
- Interactive dropdown/input widgets in Jupyter Notebook / Google Colab
- Price trend visualization (price vs year, price vs KM driven) for the selected car model
- Model evaluation via R², MAE, RMSE, and 5-fold cross-validation
- Clean and beginner-friendly code structure

## How to Run

1. **Download the project**
   - Go to the [GitHub repository]
   - Click **Code → Download ZIP**
   - Extract the ZIP file
2. **Open the notebook**
   - Open `car-price-predictor.ipynb` in Jupyter Notebook, VS Code (with Jupyter extension), or Google Colab
3. **Run the notebook**
   - The notebook is ready to run without any additional setup or installations

> Make sure the dataset file `CAR DETAILS FROM CAR DEKHO.csv` is in the same directory as the notebook (or uploaded to `/content/` if running in Google Colab).

## Dataset Source

- Original dataset: [Kaggle – Car Dekho Dataset](https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho)
