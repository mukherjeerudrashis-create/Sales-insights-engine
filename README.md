# Australian Apparel Sales Analysis (Q4 2020)

## 📌 Project Overview
This project provides a comprehensive data-driven analysis of sales performance for an Australian apparel retailer during the fourth quarter (October–December) of 2020. By examining transaction data across different states and customer demographics, this analysis identifies key revenue drivers, sales volatility, and seasonal trends to support strategic business decisions.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Library (Data Manipulation):** Pandas, NumPy
* **Library (Visualization):** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## 📂 Dataset Details
The analysis is based on the `AusApparalSales4thQrt2020.csv` dataset, which includes:
* **Dimensions:** 7,560 entries.
* **Features:** Date, Time (Morning/Afternoon/Evening), State (NSW, VIC, QLD, etc.), Customer Group (Men, Women, Kids, Seniors), Units Sold, and Total Sales revenue.

## 🚀 Analysis Workflow

### 1. Data Wrangling & Pre-processing
* **Data Integrity:** Verified zero null values across the dataset.
* **Normalization:** Applied **Min-Max Scaling** to the `Unit` and `Sales` columns to standardize values between 0 and 1, ensuring outliers do not disproportionately skew statistical comparisons.
* **Categorical Grouping:** Aggregated data by state and demographic group for granular performance tracking.

### 2. Statistical Analysis
Detailed descriptive statistics were performed to evaluate:
* **Central Tendency:** Mean, Median, and Mode for sales volume.
* **Dispersion:** Standard Deviation and variance analysis to identify sales stability across different regions.

### 3. Data Visualization
* **Distribution Analysis:** Utilized Seaborn Box Plots to visualize the spread of sales and identify significant outliers.
* **Demographic Performance:** Comparative bar charts to visualize revenue contribution by group.

### 4. Temporal Reporting
The project generates automated summaries across three time horizons:
* **Weekly Reports:** High-frequency tracking of sales fluctuations.
* **Monthly Reports:** Aggregated performance for October, November, and December.
* **Quarterly Report:** A holistic view of the total Q4 performance.

## 📈 Key Insights
* **Leading Demographic:** The **Men's** category emerged as the highest-grossing demographic group.
* **Growth Opportunity:** The **Seniors** category was identified as the lowest-performing group, suggesting a potential area for targeted marketing or inventory adjustment.
* **Regional Trends:** Detailed breakdown of sales by Australian states provided in the notebook visualizations.

## 💻 How to Use
1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/yourusername/australian-apparel-analysis.git](https://github.com/yourusername/australian-apparel-analysis.git)
    ```
2.  **Install Dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  **Run the Analysis:**
    Open `Sales_Analysis.ipynb` in Jupyter Notebook or VS Code and run all cells. Ensure the `.csv` data file is in the root directory.

---
**Author:** Rudrashis Mukherjee ( IIIT Raipur )