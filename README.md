# Google_Stock_Price_Prediction

## Project Overview
This project aims to predict Google's stock prices using historical data and machine learning techniques. The analysis is implemented in a Jupyter notebook, leveraging a Long Short-Term Memory (LSTM) neural network to forecast stock prices based on data from August 2004 to December 2023. The project includes data exploration, preprocessing, feature engineering, model training, and visualization of actual versus predicted prices.



## Dataset

The dataset (GOOG.csv) contains 4,858 records of Google's stock prices with features:
  1. Date: Trading date
  2. Open, High, Low, Close: Stock prices
  3. Adj Close: Adjusted closing price
  4. Volume: Trading volume

Source: Historical stock data (e.g., Yahoo Finance).

## Requirements
   * Python 3.8+
   * Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn, xgboost, tensorflow (for LSTM)
   * Install dependencies:

            pip install -r requirements.txt

## Project Structure
   1. Google_Stock_Price_Prediction.ipynb: Main notebook with data analysis, modeling, and visualization
   2. GOOG.csv: Dataset file
   3. README.md: Project documentation 
   4. requirements.txt: List of dependencies


## Methodology
   1. Data Exploration: Analyzed dataset for trends and consistency using pandas and seaborn.
   2. Preprocessing: Applied feature scaling with StandardScaler and engineered features (e.g., technical indicators).
   3. Modeling: Trained an LSTM model for time-series forecasting, achieving ~95% accuracy (estimated from visualization).
   4. Evaluation: Visualized actual vs. predicted prices using matplotlib.
   5. Tools: Explored LogisticRegression, SVC, and XGBClassifier but finalized with LSTM for superior performance.


## Results
   * The LSTM model accurately predicts stock prices, with visualizations showing close alignment between actual and predicted values.
   * Estimated accuracy: ~95% (based on visual inspection; precise metrics like RMSE can be added).
   * The model supports data-driven investment decisions.


## Usage
   1. Clone the repository:

          git clone https://github.com/your-username/google-stock-price-prediction.git
  
   2. Install dependencies:

          pip install -r requirements.txt

   3. Place GOOG.csv in the project directory.
   4. Run the Jupyter notebook:

               jupyter notebook Google_Stock_Price_Prediction.ipynb

## Future Improvements
  1. Incorporate external factors (e.g., market news, economic indicators).
  2. Add quantitative metrics (e.g., RMSE, MAE) for precise evaluation.
  3. Explore hybrid models combining LSTM with other algorithms.
  4. Extend with real-time data for current market relevance.

## Contributing
Contributions are welcome! Please:

  1. Fork the repository.
  2. Create a feature branch (git checkout -b feature-branch).
  3. Commit changes (git commit -m 'Add feature').
  4. Push to the branch (git push origin feature-branch).
  5. Open a pull request.

## License

This project is licensed under the MIT License. 

## Contact

For questions or feedback, open an issue or contact akshatg989@gmail.com or ask me on linkedin https://www.linkedin.com/in/01-akshat-gupta/
