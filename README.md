# Restaurant-Tips-Analysis
This project aims to use the restaurant tips dataset to examine the relationship between different variables and the tips given.
The primary goal is to identify factors that may influence tip amounts, in order to provide valuable insights for restaurant managers and service staff.

## 📊 Data Used
**Data Source:** The "Tips" dataset from the Seaborn library – a well-known dataset commonly used for teaching and practicing data analysis.

**Description:**
  - Number of records: ~244 rows
  - Attributes include: total_bill, tip, sex, smoker, day, time, size, etc.
    - total_bill: Total amount of the bill.
    - tip: Tip amount left by the customer.
    - sex: Gender of the person paying the bill.
    - smoker: Whether the customer is a smoker or not.
    - day: Day of the week.
    - time: Lunch or dinner.
    - size: Number of people at the table.

**Data Access:** The dataset is loaded directly in the notebook using the command:
```python
import seaborn as sns
df = sns.load_dataset('tips')
```
## 🎯 Main Objectives
_ Explore the dataset and its distributions.  

_ Analyze the relationships between features and tip amounts.
