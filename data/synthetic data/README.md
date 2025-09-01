# 📊 Coffee Shop Financial Dataset (Synthetic, 2022–2023)

## 📝 Overview  
This dataset simulates the financial records of a **small-town coffee shop** over a two-year period (**Jan 2022 – Dec 2023**).  
It was designed for **data science, bookkeeping, and analytics projects** — including financial dashboards, revenue forecasting, and expense tracking.  

The dataset contains **4 CSV files** representing different business accounts:  
1. **checking_account_main.csv** - Daily sales deposits (hot drinks, cold drinks, pastries, sandwiches) + operating expenses  
2. **checking_account_secondary.csv** - Monthly transfers between accounts + payroll funding  
3. **credit_card_account.csv** - Weekly credit card expenses (supplies, utilities, vendor charges) and payments  
4. **gusto_payroll.csv** - Payroll data for 3 employees + 1 contractor  

---

## 📂 File Details  

### `checking_account_main.csv`  
- date  
- description  
-category (Sales, Utilities, Rent, Supplies, etc.)  
- amount (positive = inflow, negative = outflow)  
- balance  

### `checking_account_secondary.csv`  
- date  
- description 
- amount 
- balance 

### `credit_card_account.csv`  
- date  
- vendor  
- category (Supplies, Marketing, Utilities, etc.)  
- amount (negative = charge, positive = payment)  
- balance  

### `gusto_payroll.csv`  
- date  
- employee_id  
- employee_name (Owner, Barista 1, Barista 2, Contractor)  
- role (Owner, Barista, Manager, Contractor)  
- gross_pay  

---

## 📈 Business Context  
- The coffee shop experiences **higher sales September–February** (holiday season & winter drinks).  
- Sales dip **March–June** due to seasonality in a small town.  
- Pastries are sourced from a **local bakery**, while sandwiches are made in-house.  
- Payroll includes 3 employees (baristas, manager) and 1 independent contractor.  

---

## 🎯 Possible Use Cases  
- Build a **financial health dashboard**  
- Forecast **revenue and expenses**  
- Create a **profit & loss statement**  
- Test **SQL queries for accounting workflows**  
- Explore **data visualization** with Python, R, or BI tools  
- Educational projects for **small business analytics**  

---

## 📜 License  
This dataset is released under the **MIT License**, free to use for research, learning, or commercial purposes.  

---

⭐ If you use this dataset in your project or notebook, please **credit and share your work**, it helps the community!  

---

💡 Kaggle Dataset can be found [here](https://www.kaggle.com/datasets/gabriellecharlton/coffee-shop-financial-dataset-synthetic-2022-2023) 

---

📷 Photo Credits: freepik
