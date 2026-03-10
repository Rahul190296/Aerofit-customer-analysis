# 📊 Aerofit Customer & Product Analysis

## 🧩 Business Problem

Aerofit is a fitness equipment company that sells three treadmill models:

* **KP281** – Entry level
* **KP481** – Mid level
* **KP781** – Premium level

The company wants to understand **which customer segments are more likely to purchase each treadmill model** so that they can improve **marketing strategy, product positioning, and customer targeting**.

This project analyzes customer demographic and usage data to identify **patterns in purchasing behavior**.

---

# 📂 Dataset Information

The dataset contains **180 customer purchase records** with the following attributes:

| Column        | Description                     |
| ------------- | ------------------------------- |
| Product       | Treadmill model purchased       |
| Age           | Customer age                    |
| Gender        | Male / Female                   |
| Education     | Years of education              |
| MaritalStatus | Single / Partnered              |
| Usage         | Expected weekly treadmill usage |
| Fitness       | Self-rated fitness level        |
| Income        | Annual income                   |
| Miles         | Expected miles run per week     |

---

# 🛠 Tools & Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook / Google Colab**

---

# 🔧 Data Cleaning & Feature Engineering

Several new variables were created to improve analysis:

### Product Tier

Products were categorized into tiers:

| Product | Tier    |
| ------- | ------- |
| KP281   | Entry   |
| KP481   | Mid     |
| KP781   | Premium |

### Age Groups

Customers were segmented into age groups:

* 17–25
* 26–35
* 36–40
* 41–60

### Usage Level

Weekly treadmill usage was categorized as:

* Low
* Medium
* High

### Fitness Level

Fitness levels were grouped into:

* Low
* Medium
* High

Outliers in numerical columns were treated using **5th and 95th percentile clipping**.

---

# 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

### Customer Demographics

* Age distribution
* Income distribution
* Marital status distribution

### Product Analysis

* Product purchase by gender
* Product purchase by marital status
* Product purchase by age group

### Behavioral Analysis

* Income vs product tier
* Fitness level vs product tier
* Weekly usage patterns

### Correlation Analysis

Correlation matrix was created to understand relationships between:

* Income
* Usage
* Fitness
* Miles
* Education

---

# 📈 Key Insights

### 1️⃣ Entry-Level Product is Most Popular

KP281 has the **highest purchase probability (~44%)** among all products.

---

### 2️⃣ Male Customers Prefer Premium Products

Male customers show a **higher probability of purchasing premium treadmill KP781** compared to female customers.

---

### 3️⃣ Younger Customers Prefer Entry-Level Products

Customers in the **17–25 age group mainly purchase entry-level treadmills**.

---

### 4️⃣ Income Influences Product Choice

Higher-income customers are more likely to purchase **premium treadmill models**.

---

### 5️⃣ Fitness Level and Usage Impact Purchases

Customers with **higher fitness levels and higher weekly usage** are more likely to purchase **premium treadmills**.

---

# 📉 Probability Analysis

Marginal probability of purchasing each product:

| Product | Probability |
| ------- | ----------- |
| KP281   | 44%         |
| KP481   | 33%         |
| KP781   | 22%         |

---

# 🔗 Correlation Insights

Strong correlations observed:

| Relationship           | Correlation        |
| ---------------------- | ------------------ |
| Fitness ↔ Miles        | Strong             |
| Usage ↔ Miles          | Strong             |
| Income ↔ Product Price | Moderate to Strong |

This indicates that **more active customers tend to run more miles and prefer higher-tier products**.

---

# 📊 Example Visualizations

The analysis includes visualizations such as:

* Age Distribution
* Income Distribution
* Product Purchase by Gender
* Product Tier vs Fitness Level
* Income vs Usage Scatter Plot
* Correlation Heatmap

---

# 💡 Business Recommendations

Based on the analysis:

* **Target high-income and high-fitness customers** for premium treadmill marketing.
* Promote **entry-level products to younger customers**.
* Use **fitness level and weekly usage** as key customer segmentation features.
* Develop marketing campaigns focused on **active lifestyle segments**.

---

# 📁 Project Structure

```
aerofit-customer-analysis
│
├── data
│   └── Aerofit.csv
│
├── notebooks
│   └── aerofit_analysis.ipynb
│
├── images
│   └── visualizations
│
└── README.md
```

---

# 🚀 Project Outcome

This analysis helps Aerofit:

* Identify **target customer segments**
* Improve **product positioning**
* Support **data-driven marketing strategies**

---

# 👨‍💻 Author

Rahul Pandey
Aspiring Data Analyst

Skills:

* Python
* SQL
* Power BI
* Tableau
* Machine Learning
