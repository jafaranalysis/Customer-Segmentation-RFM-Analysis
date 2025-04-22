# 📊 Customer Segmentation using RFM Analysis

## 📌 Overview  
This project segments retail customers based on their purchasing behavior using **RFM analysis** (Recency, Frequency, Monetary). The goal is to identify high-value customers (e.g., "Champions") and at-risk customers to optimize marketing strategies.

## 🛠️ Tools Used  
- Python (Pandas, NumPy, Matplotlib)  
- Jupyter Notebook  
- Regex for dynamic segmentation  

## 📥 Installation  
1. Clone the repository:  
   `git clone https://github.com/yourusername/rfm-analysis.git`  
2. Install dependencies:  
   `pip install -r requirements.txt`  

## 🚀 Workflow  
1. **Data Cleaning**:  
   - Remove missing values .  
   - Filter out canceled orders.  
2. **RFM Calculation**:  
   - **Recency**: Days since the last purchase.  
   - **Frequency**: Number of unique transactions.  
   - **Monetary**: Total money spent.  
3. **Scoring & Segmentation**:  
   - Assign scores (1-5) for each metric.  
   - Combine scores into `RFM_score` (e.g., "53" = R=5, F=3).  
   - Map scores to segments using Regex.  

## 📂 Project Structure  
├── data/

│ └── Online_Retail.xlsx # Raw transaction data

├── notebooks/

│ └── RFM_Analysis.ipynb # Full analysis workflow

├── src/

│ └── rfm_utils.py # Helper functions

└── README.md

         ## 📈 Key Insights  
| Segment          | Recommendation                          |  
|------------------|-----------------------------------------|  
| **Champions**    | Offer exclusive rewards                 |  
| **At Risk**      | Send personalized discounts             |  
| **Hibernating**  | Re-engage via email campaigns           |  

## 🤝 Contribution  
- Fork the repo and submit pull requests.  
- Report issues or suggest improvements.

## 💡 Challenges  
- Handling negative quantities (canceled orders).  
- Balancing segments for skewed data (e.g., 80% UK customers).  





