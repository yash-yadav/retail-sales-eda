

```markdown
# 🛒 Retail Sales Exploratory Data Analysis (EDA)

An end-to-end Exploratory Data Analysis (EDA) project focused on analyzing retail store transactions, identifying sales trends, evaluating pricing distributions, and deriving actionable business insights.

---

## 📁 Repository Structure

```text
EDA/
│
├── Data/
│   └── retail_sales_dataset.csv     # Raw retail transaction dataset
│
├── .gitignore                       # Unwanted system/checkpoint files filter
├── README.md                        # Portfolio documentation & insights summary
├── requirements.txt                 # Dependencies and library versions
└── runner_eda.ipynb                 # Clean Jupyter Notebook with visualizations

```

---

## 📊 Dataset Overview

The dataset contains transactional records capturing retail sales performance across multiple product categories, customer demographics, and timeframes.

* **Primary Attributes:** Date, Customer ID, Gender, Age, Product Category, Quantity, Price per Unit, and Total Amount.
* **Target Numerical Metrics:** `Price per Unit`, `Quantity`, `Total Amount`.
* **Categorical Dimensions:** `Gender`, `Product Category`.

---

## 📈 Chart-by-Chart Analysis & Insights

### 1. Demographic & Age Distribution Analysis

* **Customer Age Range:** Customer age spans across a wide range (up to 60+ years), with both the mean and median age centered at **~40 years**.
* **Even Distribution:** The distribution is balanced across all age groups with no extreme age outliers.

### 2. Category Spending by Gender

* **Female Preferences:** Female shoppers drive higher overall sales volume and spending in the **Beauty** and **Clothing** categories.
* **Male Preferences:** Male shoppers generate the majority of spending within the **Electronics** category.

### 3. Total Revenue by Product Category

* **Revenue Breakdown:** **Electronics** leads total sales volume at **$156,905**, closely followed by **Clothing** at **$155,580**, and **Beauty** at **$143,515**.
* **Basket Size Effect:** Electronics achieves the top revenue position primarily due to higher unit price points per transaction rather than higher order volumes.
* **Balanced Portfolio:** Revenue across all three product categories is evenly distributed, reducing overall business dependence on a single category.

### 4. Outlier & Distribution Analysis (Price vs. Total Amount)

* **Price per Unit:** Demonstrates a highly balanced and uniform distribution spanning from **$18 to $64**, with a median unit price of approximately **$42**. No statistical outliers are observed in individual product pricing.
* **Total Amount Spread:** Displays a right-skewed distribution where the median transaction value sits at **~$135**, with 50% of total bills ranging between **$60 and $900**. High-value orders reach up to **$2,000** due to multi-unit quantity purchases, without generating extreme statistical anomalies.

### 5. Category-Wise Distribution Analysis

* **Beauty & Electronics:** Both categories exhibit a wider interquartile range (IQR) spanning up to **$900**, with maximum transaction values reaching **$2,000**. No statistical outliers are observed in either category.
* **Clothing Anomalies:** Shows a lower overall spending concentration with the main box limited to **~$600** and the upper whisker extending to **$1,200**. Clothing displays **two distinct statistical outliers at $1,500 and $2,000**, representing unusually large bulk purchases.

### 6. Monthly Revenue Trends

* **Peak Sales Performance:** Monthly revenue reaches its highest peak in **May (~$53,000)**, followed by strong secondary peaks in **October (~$46,500)** and **December (~$44,500)**.
* **Mid-Year Dip:** The lowest sales period occurs in **September (~$23,500)**, showing a temporary reduction in purchasing before the Q4 surge.

### 7. Revenue by Day of Week

* **Weekend Surge:** **Saturday** generates the highest overall revenue at **$78,815**, driven by weekend shopper traffic.
* **Mid-Week Low:** Revenue drops to its lowest point on **Thursday ($53,835)** before recovering on Friday ($66,290).
* **Early-Week Momentum:** **Monday ($70,250)** and **Tuesday ($69,440)** perform exceptionally well, highlighting strong early-week sales momentum.

---

## 🎯 Strategic Business Recommendations

1. **Cross-Selling & Basket Expansion:**
Combine high-ticket **Electronics** items with relevant **Clothing** or accessory add-ons to increase the total checkout value.
2. **High-Value Outlier Targeting:**
Implement structured loyalty or bulk-buying discounts to convert occasional **$1,500+ Clothing purchasers** into regular high-ticket clients.
3. **Optimized Marketing Schedules:**
Schedule promotional pushes, promotional emails, and flash sales on **Sunday evenings/Monday mornings** to leverage early-week momentum alongside Saturday peaks.
4. **Q3 Sales Stabilization:**
Introduce mid-year promotional campaigns or clearance sales during **August–September** to offset the seasonal revenue drop before Q4.
5. **Personalized Category Targeting:**
Customize store recommendations based on customer profiles—promoting **Beauty & Clothing** to female demographics and **Electronics** to male demographics.

---

## 🛠️ Installation & Usage

1. **Clone the repository:**
```bash
git clone [https://github.com/your-username/retail-sales-eda.git](https://github.com/yash-yadav/retail-sales-eda.git)
cd EDA

```


2. **Install required dependencies:**
```bash
pip install -r requirements.txt

```


3. **Launch the Jupyter Notebook:**
```bash
jupyter notebook runner_eda.ipynb

```



---

*Developed as part of Data Analysis & Exploratory Data Analysis Portfolio Project.*

```

```