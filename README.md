# Restaurant-Tips-Analysis
This project aims to use the restaurant tips dataset to examine the relationship between different variables and the tips given.
The primary goal is to identify factors that may influence tip amounts, in order to provide valuable insights for restaurant managers and service staff.

## 📊 Data Used
**Data Source:** The "Tips" dataset from the Seaborn library – a well-known dataset commonly used for teaching and practicing data analysis.

**Description:**
   Number of records: ~244 rows
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
- Explore the dataset and its distributions.  
- Analyze the relationships between features and tip amounts.

## 📈 Primary Results
After exploring the data across variables like smokers, time, sex, day,..., we found some interesting things:

- Smokers don’t tip more than non-smokers.
- Men also don't tend to tip more than women. Or Male smokers tip more than male non-smokers .
- There's a noticeable difference in tip amounts between lunch and dinner. And Tips tend to be higher on weekends. [Learn more](https://github.com/letuanGithubVn1/Restaurant-Tips-Analysis/blob/main/Restaurant_tips_analysis.ipynb)

## 🚀 Usage Instructions
Clone the repository, install the required libraries, and launch the Restaurant_tips_analysis.ipynb notebook using Jupyter Notebook or Google Colab.

``` python
pip install pandas matplotlib notebook
jupyter notebook Restaurant_tips_analysis.ipynb
```
**Note**: Make sure to install the seaborn library if you want to load the dataset directly.


