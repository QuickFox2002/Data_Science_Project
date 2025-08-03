## Task 3: Customer Segmentation

### Objective
Cluster customers into groups based on purchasing behavior to better understand and target different market segments.

### Dataset
- **Mall_Customers.csv**
- Columns:
  - `CustomerID` — Unique identifier for each customer
  - `Gender` — Male/Female
  - `Age` — Age of the customer
  - `Annual Income (k$)` — Annual income in thousands
  - `Spending Score (1-100)` — Score assigned based on spending habits

### Methodology
- Data preprocessing
- Determining optimal cluster count using the Elbow Method
- Clustering using **KMeans**
- Visualization of customer segments

### How to Run
```bash
pip install pandas matplotlib seaborn scikit-learn
python task3_customer_segmentation.py