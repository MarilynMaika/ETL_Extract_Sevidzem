
##  ETL Extract Lab

**Name:** Sevidzem Marilyn  


---

##  Project Description

This project demonstrates the **Extraction phase** of an ETL (Extract, Transform, Load) pipeline using **randomly generated user data** and simulated full/incremental extraction strategies.

The notebook shows:
- How to generate fake user data using Python.
- How to perform **full extraction** from a CSV file.
- How to simulate **incremental extraction** using a `last_updated` timestamp.
- How to save and reuse a checkpoint to avoid reprocessing old data.

---

##  Tools Used

- Python
- Pandas
- NumPy
- Jupyter Notebook
- CSV for data storage

---

##  How to Reproduce

### 1. Clone or download this repository.

### 2. Run the Jupyter notebook:
Make sure you have Python and the required packages installed:
### Screenshots

![image](https://github.com/user-attachments/assets/72eccef7-dba7-4e56-9cf6-3487666a100b)
![image](https://github.com/user-attachments/assets/05f6a928-4cac-40af-aa7c-96e12c37b7ee)

##  Transformations Applied

I applied the following transformations to both the full and incremental datasets:

1. **Cleaning:** Removed duplicate records
2. **Enrichment:** Added age group column based on user age
3. **Structural:** Standardized datetime format for `last_updated`

Transformed datasets are saved as:
- `transformed_full.csv`
- `transformed_incremental.csv`








