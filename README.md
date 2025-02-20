# Stock Sector Similarity Analysis and Classification

## Project Purpose
This project aims to analyze the time series behavior of stocks from different sectors and classify stocks based on their sectoral similarities. The insights gained from this classification can be used to refine investment strategies.

## Project Summary

### Data Collection
- Financial data from different sectors was gathered using web scraping.
- Monthly stock data for companies in the Financials, Healthcare, and Technology sectors was downloaded using the `yfinance` library and saved.

### Data Preprocessing
- Missing values were handled using appropriate imputation techniques.
- Time series transformations like differencing and log transformations were applied for stationarity.
- Categorical sector information was converted into numerical values using encoding methods.
- Data was standardized for better model performance.

### Feature Extraction & Selection
- Statistical features were extracted from the time series using the `tsfresh` library.
- Feature selection techniques like Lasso regularization and Principal Component Analysis (PCA) were applied.

### Model Development & Evaluation
- Machine learning models such as Random Forest, Gradient Boosting, XGBoost, and CatBoost were trained for classification.
- Cross-validation was used to evaluate the models, and metrics like accuracy, precision, recall, and F1-score were computed.

### Sector Similarity Analysis
- The classification results were analyzed to determine which stocks exhibited similarities to different sectors.
- Additional financial indicators such as momentum, volatility, and moving averages were explored for further improvements.

## Technologies Used
- **Programming Language:** Python
- **Libraries:** `yfinance`, `tsfresh`, `scikit-learn`, `XGBoost`, `CatBoost`, `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`

## Future Enhancements
- Extend the analysis to more sectors.
- Implement deep learning techniques for better classification accuracy.
- Develop a web dashboard for real-time stock classification insights.

## How to Use
1. Run the data collection script to fetch stock market data.
2. Execute the preprocessing and feature extraction modules.
3. Train and evaluate the machine learning models.
4. Analyze sector similarity results.

## License
This project is open-source and available under the MIT License.

---

For more details, feel free to check out the project repository or contact the contributors.

