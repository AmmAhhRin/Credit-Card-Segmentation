# Credit Card Segmentation using K-Means Clustering

This project aims to segment credit card customers using **K-Means clustering** and analyze one selected cluster through an interactive **Power BI dashboard**. The objective is to uncover insights into customer behavior to support better decision-making for marketing and credit strategies.

---

## Project Workflow

### 1. **Data Preprocessing**
- Loaded and cleaned credit card customer data, including variables such as **balance, purchases, credit limit, tenure, and payment behavior**.
- Scaled numerical features to ensure optimal clustering performance.
- Handled missing values and removed outliers to improve clustering accuracy.

### 2. **K-Means Clustering**
- Determined the optimal number of clusters (`k=5`) using the **elbow method**.
- Applied **K-Means** to segment customers based on their payment, balance, and usage patterns.
- Analyzed cluster characteristics by aggregating feature statistics for each group.

### 3. **Cluster Selection for Deeper Analysis**
- Selected **Cluster 5** (KM5_5)
 
---

## Power BI Dashboard Highlights (KM5_5 Analysis)

The dashboard focuses on profiling the customers in the selected cluster (Cluster 5):
### Key Insights:
- **Demographics**:
  - Gender Split: 69% Female, 31% Male
  - Most customers are **Married (86%)**
  - Dominant age group: **36–45 years**

- **Occupational Distribution**:
  - 50% are **Employed**
  - Other groups: Self-employed (19%), Students (16%), Retired (10%)

- **Spending & Credit**:
  - Avg. Credit Limit: **$4.54K**
  - Avg. Limit Usage: **29%**
  - Avg. Balance: **$1,071**, with max values up to $15,532

- **Payment Behavior**:
  - Majority make payments in the **$1,000–$1,999** range
  - Fewer in low (<$200) or very high ($2,000+) brackets

---

## Business Implications
- **Targeted Promotions**: Focus marketing campaigns on employed individuals aged 36–45 with moderate spending.
- **Credit Management**: These users maintain a healthy balance-to-limit ratio, making them ideal for credit limit increases.
- **Retention Strategy**: Offer rewards or personalized offers to maintain engagement with this stable and valuable segment.

---

## Project Files
- `Credit_Card_Segmentation_KMeans.ipynb`: Jupyter notebook for the full clustering implementation. There are more analyses on the data in there, along with the flow of statistical analysis of the dataset, running the model, and selecting a cluster.
- `KM5_5_Analysis.pbix`: Power BI dashboard for in-depth analysis of the selected cluster
- `Cluster Profile.csv`: The output of all the segments with their characteristics and features
- `Selected Cluster.csv`: The data used for creating the Power BI dashboard

---
If there are inquiries regarding the project, please contact:

Email: somphorsyun24@gmail.com
LinkedIn: www.linkedin.com/in/somphorsyun
