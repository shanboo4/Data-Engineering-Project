# Sales Data - Delta Lake Project

This project demonstrates how to use **Databricks with PySpark & Delta Lake** for a mini end-to-end data engineering workflow.

## 🚀 Features
- Load CSV into Spark DataFrame
- Convert to Delta Lake format
- Perform Aggregations & Filters
- Delta Lake DML Operations:
  - UPDATE
  - DELETE
  - MERGE (Upserts)
- Time Travel (query historical versions)
- VACUUM & OPTIMIZE

## 🛠️ Requirements
- Databricks Community Edition (Free)
- Spark (comes pre-installed with Databricks)
- Delta Lake (enabled by default in Databricks)

## 📂 Files
- `sales_data_delta_project.ipynb` → Main notebook with step-by-step code & markdowns
- `sample_data.csv` → Example dataset (upload via Databricks → Workspace → Upload File)

## ▶️ How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/<your-username>/sales-data-delta-lake.git
   ```
2. Import the notebook into Databricks:
   - Go to **Workspace → Import → Upload**
   - Select `sales_data_delta_project.ipynb`
3. Upload `sample_data.csv` into your Databricks workspace
4. Run the notebook step by step

## 📊 Sample Queries
- Top products by revenue
- Orders by customer
- Historical snapshots using Delta **Time Travel**

## 📸 Screenshots
*(Optional: you can add screenshots of your Delta table queries here)*

---

💡 This project is part of my **Data Engineering portfolio** — showcasing Spark & Delta Lake skills in Databricks.
