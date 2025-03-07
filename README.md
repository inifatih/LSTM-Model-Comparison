# LSTM Model Comparison

## 📌 Background
Deep learning is increasingly used in time series prediction, with **Long Short-Term Memory (LSTM)** being one of the popular approaches. In this project, we compare three different LSTM architectures to determine the best-performing model for time series forecasting.

## 🎯 Research Objectives
1. Compare the performance of **Bidirectional LSTM**, **Stacked LSTM**, and **Vanilla/Simple LSTM**.
2. Identify the best model based on **MSE, RMSE, and MAPE** metrics.
3. Save the best model for future predictions.

## 📊 Dataset
- The dataset used is **Superstore Sales Dataset** from https://www.kaggle.com/datasets/ishanshrivastava28/superstore-sales, which contains sales transaction data from a retail store.
- The dataset consists of **21 features** and includes **order details, customer information, product categories, and financial metrics like sales, discount, and profit**.
- Data is preprocessed using **MinMaxScaler normalization** before being fed into the models.

### 📜 Dataset Metadata
| Feature | Description |
|---------|-------------|
| Row ID | Unique ID for each row |
| Order ID | Unique Order ID for each Customer |
| Order Date | Date when the order was placed |
| Ship Date | Date when the product was shipped |
| Ship Mode | Shipping mode specified by the customer |
| Customer ID | Unique ID for each customer |
| Customer Name | Name of the customer |
| Segment | Customer segment |
| Country | Country of residence of the customer |
| City | City of residence of the customer |
| State | State of residence of the customer |
| Postal Code | Postal code of the customer |
| Region | Region where the customer belongs |
| Product ID | Unique ID of the product |
| Category | Category of the ordered product |
| Sub-Category | Sub-category of the ordered product |
| Product Name | Name of the product |
| Sales | Sales revenue of the product |
| Quantity | Quantity of the product ordered |
| Discount | Discount applied to the product |
| Profit | Profit or loss incurred |

## 🔍 Research Findings
| Model | MSE | RMSE | MAPE |
|--------|------|------|------|
| Bidirectional LSTM | xx.xx | xx.xx | xx.xx% |
| Stacked LSTM | xx.xx | xx.xx | xx.xx% |
| Vanilla LSTM | xx.xx | xx.xx | xx.xx% |

- The best-performing model is **Stacked LSTM**, as it has the lowest MSE, RMSE, and MAPE.
- Prediction results indicate that this model captures time series patterns better than the other models.

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-github-username/LSTM-Model-Comparison.git
   cd LSTM-Model-Comparison
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the training script:
   ```bash
   LSTM_Time_series_Prediction.ipynb
   ```
4. The trained model will be saved in `.h5` format.

## 📌 Conclusion
- The **Stacked LSTM** model performed the best in time series forecasting.
- The choice of LSTM architecture significantly impacts prediction accuracy.
- This model can be used for **sales forecasting, inventory management, and business decision-making**.

## 🔗 References
1. [https://www.sciencedirect.com/science/article/pii/S2667096822000027]
