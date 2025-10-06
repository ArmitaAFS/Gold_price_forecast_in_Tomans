# 💰 24K Gold Price Prediction in Toman using Polynomial Regression 📈

This project predicts the price of **24K gold** in **Toman** based on the date.  
The prediction model used is a **5th-degree polynomial regression**.

## 🚀 Project Steps

1. **📚 Importing Libraries**  
   All necessary libraries for data processing, modeling, and visualization were imported.

2. **🗂 Loading & Preprocessing Data**  
   - Dataset was loaded and cleaned.  
   - Irrelevant or unusable values were removed.  
   - Dates were converted into numerical day counts to be used as input features.

3. **🤖 Model Training**  
   - First, a simple **linear regression** model was trained as a baseline.  
   - Then, a **5th-degree polynomial regression** model was trained and compared with the linear model.

4. **📊 Visualization**  
   - Predictions from both linear and polynomial models were visualized for comparison.

5. **✅ Model Validation**  
   - **K-Fold Cross-Validation** was applied to ensure accuracy.  
   - The 5th-degree polynomial gave the best results.

6. **🧪 Testing & Metrics**  
   - New data points were tested with the model.  
   - Evaluation metrics:
     - **R² Score:** Very close to 1, indicating excellent fit.  
     - **Mean Squared Error (MSE):** Low, showing accurate predictions.

## 🎯 Conclusion

The **5th-degree polynomial regression** model provides highly accurate predictions of 24K gold prices in Toman based on historical data, outperforming simple linear regression.  
Perfect for financial analysis and forecasting trends! 💹
