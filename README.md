# Expense-Tracker-using--Python
This is a simple expense tracker built in Python using Pandas, NumPy, and Matplotlib.

## Features
- Read expenses from a CSV file (`expenses.csv`)
- Display:
  - Total spent
  - Highest and lowest expense
  - Category-wise summary (total spent, transaction count, percentage of total)
- Optional pie chart visualization of spending by category
- Filter by a date range
- Add new expenses and save back to CSV
- Save a summary report as `summary_report.csv`
## How to Run

1. **Install the required dependencies**:
   ```bash
   pip install pandas numpy matplotlib
2. **Place your expenses.csv file in the same directory as the notebook (expense_tracker.ipynb).**

3. **Launch Jupyter Notebook**:
    ```bash
    jupyter notebook
4. **Open the expense_tracker.ipynb file in the Jupyter interface.**

5. **Run all the code cells sequentially**:

- Go to Cell → Run All, or

- Select each cell and press Shift+Enter.
## Features Implemented

✅ **Total Spending Overview**  
- Calculates the total amount spent.
- Identifies the highest and lowest expense records.

✅ **Category-wise Analysis**  
- Displays the total spending per category.
- Counts the number of transactions per category.
- Computes the percentage contribution of each category to total spending.

✅ **Visualizations**  
- Pie chart that shows spending as a proportion of each category.

✅ **Date Filtering**  
- Filter expenses for a specific date range.

✅ **Add New Expenses**  
- Append new expense records dynamically and save them back to `expenses.csv`.

✅ **Generate Summary Report**  
- Export a CSV file (`summary_report.csv`) with category-wise summaries.
---

## Sample Input

Your `expenses.csv` file should look like this:

| Date       | Category  | Amount | Description      |
| ---------- | --------- | ------ | ---------------- |
| 2025-06-10 | Food      | 150    | Pizza at Dominos |
| 2025-06-11 | Transport | 50     | Rickshaw fare    |
| 2025-06-12 | Rent      | 5000   | June Rent        |
| 2025-06-12 | Utilities | 200    | Electricity Bill |

---

## Sample Output

**Example Total Spending Overview:**
Total spent overall: 5400

Highest expense:
| Date       | Category | Amount | Description | Name |
| ---------- | -------- | ------ | ----------- | ---- |
| 2025-06-12 | Rent     | 5000   | June Rent   | 2    |

Lowest expense:
| Date       | Category  | Amount | Description   | Name |
| ---------- | --------- | ------ | ------------- | ---- |
| 2025-06-11 | Transport | 50     | Rickshaw fare | 1    |

**Example Category-wise Summary:**

| Category  | Total Amount | Transaction Count | Percentage of Total (%) |
| --------- | ------------ | ----------------- | ----------------------- |
| Food      | 150          | 1                 | 2.78                    |
| Rent      | 5000         | 1                 | 92.59                   |
| Transport | 50           | 1                 | 0.93                    |
| Utilities | 200          | 1                 | 3.70                    |

## 📊 Pie Chart Visualization

And the pie chart will show a visual representation of your expenses by category:

- Quickly identify major spending categories at a glance.
- Easy to customize colors, labels, and size.

---
