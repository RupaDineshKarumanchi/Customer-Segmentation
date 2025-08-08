# Customer-Segmentation
This project implements **Customer Segmentation** for an online retail dataset using **RFM (Recency, Frequency, Monetary) analysis**.  
It preprocesses, transforms, and scores customers based on their purchasing patterns, helping businesses identify key customer groups for targeted marketing.

Customer segmentation is the process of dividing customers into groups based on shared characteristics or behaviors.  
Here, we use **RFM metrics** to classify customers into meaningful segments:

- **Recency (R):** How recently a customer made a purchase.
- **Frequency (F):** How often they purchase.
- **Monetary (M):** How much they spend.

The workflow includes:
1. Data cleaning & preprocessing
2. Feature engineering for R, F, M values
3. Cube-root transformation to normalize skewed data
4. Scoring customers using quartile-based ranking
5. Creating an **RFM Score** for segmentation

## 📂 Dataset
- **Source:** Online Retail transactional dataset (CSV)
- **Columns used:** `CustomerID`, `InvoiceDate`, `InvoiceNo`, `Quantity`, `UnitPrice`

---

## 🛠️ Tech Stack
- **Python**: Pandas, NumPy, Matplotlib, Seaborn
- **Jupyter Notebook**: For exploration and analysis
- **Scikit-learn**: For future clustering (optional)

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation-rfm.git
   cd customer-segmentation-rfm
2. Run the notebook or Python script:
   ```bash
   jupyter notebook customer_segmentation.ipynb

📊 Key Steps
1.Data Cleaning
2. RFM Metric Calculation
3. Cube-root Transformation: Applied to normalize skewness in the data.
4.Scoring


