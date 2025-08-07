# GUVI-HCL-PROJECT-2
⚡ Electricity Consumption Monitor

📌 Project Overview  
The Electricity Consumption Monitor analyzes hourly electricity usage data to visualize consumption trends, detect peak hours, and apply machine learning models for consumption prediction. This helps households and companies optimize energy usage and reduce electricity bills.

🔍 Problem Statement  
Households and businesses often lack insights into their electricity consumption patterns. This project visualizes usage over time and applies ML to identify high-consumption periods and suggest reduction strategies.

📈 Key Features  
- Load and process timestamped consumption data  
- Time series visualization (hourly, daily, weekly trends)  
- Peak hour and anomaly detection  
- Electricity bill estimation (based on per unit cost)  
- Predictive modeling using:  
  - Linear Regression  
  - Random Forest Regressor  
- Summary statistics and EDA (Exploratory Data Analysis)  
- Cost-saving tips based on high-usage patterns  

📊 Sample Input  
DateTime               | Units  
----------------------|-------  
2025-07-01 09:00:00   | 2.3  
2025-07-01 10:00:00   | 1.8  

✅ Output Example  
- Total Units (July): 520 kWh  
- Estimated Bill: ₹3120  
- Peak Usage Hours: 6 PM – 9 PM  

🧠 ML Models Used  
- Linear Regression for consumption prediction  
- Random Forest Regressor for robust forecasting  
- Evaluation metrics: MAE, MSE, R² Score  

🛠 Tech Stack  
- Language: Python  
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- Environment: Jupyter Notebook  

🧪 How to Run  
1. Clone the repo or download files  
2. Install required libraries:  
   `pip install pandas numpy matplotlib seaborn scikit-learn`  
3. Run the notebook:  
   `jupyter notebook Electricity_Consumption_Monitor_July_2025.ipynb`  

📁 Project Structure  
📦 Electricity-Consumption-Monitor/  
├── electricity_consumption_july2025.csv  
├── Electricity_Consumption_Monitor_July_2025.ipynb  
├── README.txt  

📬 Contact  
For questions, feel free to reach out to Ronit Kumar (IIT Patna).
