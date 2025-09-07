# CO₂ Emissions Prediction Project 

This project focuses on analyzing and predicting **vehicle CO₂ emissions** using the official **CO₂ Emissions dataset (Canada)**.  
The goal is to study the relationship between vehicle specifications (engine size, cylinders, fuel consumption) and CO₂ emissions, then apply machine learning models to predict emissions.  
Finally, the trained models are used to estimate **CO₂ emissions for three engines**: **TU5, XU7, and EF7**.

---

##  Dataset
The dataset used in this project is the **CO2 Emissions_Canada.csv**, which includes:
- Engine Size (L)  
- Cylinders  
- Fuel Consumption (City, Highway, Combined)  
- Fuel Consumption (mpg)  
- CO₂ Emissions (g/km)  

Dataset source: [Government of Canada - CO2 Emissions Dataset](https://open.canada.ca)

---

## ⚙ Project Workflow
1. **Data Exploration & Visualization**  
   - Distribution of CO₂ emissions  
   - Relationship between engine size, cylinders, and emissions  
   - Average emissions by fuel type  
   - Correlation heatmap  

2. **Feature Selection & Preprocessing**  
   - Selected relevant numeric features  
   - Standard scaling applied  

3. **Model Training & Evaluation**  
   Multiple regression models were trained and compared using metrics **MSE, MAE, and R²**:  
   - Linear Regression  
   - Decision Tree Regressor  
   - Random Forest Regressor  
   - Gradient Boosting Regressor  
   - Multi-layer Perceptron (Neural Network)  
   - Support Vector Regressor (SVR)  

4. **Model Comparison**  
   - Performance comparison with bar charts (MSE, MAE, R²)  

5. **Predictions for Engines**  
   - TU5, XU7, EF7 parameters were used to predict CO₂ emissions.   

---

##  Results
- **TU5**: Lower emissions, relatively more efficient  
- **EF7**: Mid-range emissions, acceptable for its size  
- **XU7**: Higher emissions, less efficient compared to the others  

Example visualization of predictions:

![CO2 Predictions](assets/co2_predictions.png)

---

##  Technologies Used
- **Python 3.x**  
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn  

---

##  How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/abolfazlkarimi83/CO2-Emissions-Prediction.git
   cd CO2-Emissions-Prediction
   ```

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:  
   ```bash
   jupyter notebook CO2_Emissions_Prediction.ipynb
   ```

---

##  Future Improvements
- Add hyperparameter tuning for better model optimization  
- Extend dataset with more recent emissions data  
- Deploy as a web app for real-time predictions  

---

##  Author
If you'd like to connect or discuss this project, feel free to reach out:

-  Email: [karimiabolfazl466@gmail.com](karimiabolfazl466@gmail.com)
- Telegram: [@Abolfazlk83](https://t.me/Abolfazlk83)  
- LinkedIn: Coming soon  
- GitHub: [github.com/abolfazlkarimi83](https://github.com/abolfazlkarimi83)

---
If you find this project useful, please ⭐ the repo and share it!  
