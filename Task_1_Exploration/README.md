# 📊 Task 1: Exploring and Visualizing a Simple Dataset

## ✅ Objective

The objective of this task was to **load, inspect, and visualize the Iris dataset** to understand data trends, distributions, and detect potential outliers.  
This helps build a solid foundation in **data exploration**, which is essential for any AI/ML project.

---

## 📂 Dataset Used

- **Name:** Iris Dataset  
- **Source:** Seaborn library (`sns.load_dataset('iris')`) or CSV format (publicly available)  
- **Description:** Classic dataset containing 150 samples of iris flowers with four numerical features: `sepal_length`, `sepal_width`, `petal_length`, `petal_width` and one categorical target: `species`.

---

## ⚙️ Steps Performed

- Loaded the dataset using **pandas**.
- Printed the **shape**, **column names**, and first few rows (`.head()`).
- Used `.info()` and `.describe()` for **summary statistics**.
- Visualized the dataset using:
  - **Scatter plots** to show relationships between features.
  - **Histograms** to display value distributions.
  - **Box plots** to detect outliers.

---

## 🧩 Skills Practiced

- Data loading and inspection with **pandas**
- Descriptive statistics and EDA
- Basic plotting and visualization using **matplotlib** and **seaborn**

---

## ✅ Key Results and Findings

- **Data integrity:** No missing values found in the dataset.
- **Feature relationships:** Scatter plots revealed clear separations between species based on petal length and petal width.
- **Value distributions:** Histograms showed that some features are **skewed** while others are fairly normally distributed.
- **Outlier detection:** Box plots identified a few potential outliers, especially in `sepal_width`.

---

## 📁 Files Included

- `iris_exploration.ipynb` — Jupyter Notebook containing all code, plots, and step-by-step explanations.
- This `README.md` — Task summary and insights.

---

## 🔗 References

- [Iris Dataset - Seaborn Docs](https://seaborn.pydata.org/generated/seaborn.load_dataset.html#seaborn.load_dataset)
- [Original Iris Dataset - UCI Repository](https://archive.ics.uci.edu/ml/datasets/iris)

---

**✅ Task Completed Successfully**  
