# Genesis-Analytics-Bootcamp
My final project

## Interactive Dashboard
🔗 **Tableau Public:** 
https://public.tableau.com/views/PaymentAnalysis_17658106478970/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---
## Dataset Description

**Dataset size:**  
- **566,413 rows × 13 columns**

### Data Fields
- **order_id** — unique identifier of the payment order  
- **event_time** — date and time of the transaction  
- **user_id** — unique identifier of the user  
- **price** — transaction amount in the specified currency  
- **payment_number** — transaction type (*initial* or *recurring*)  
- **transaction_status** — transaction outcome (*success* or *fail*)  
- **card_brand** — card brand (Visa, Mastercard, Amex, etc.)  
- **card_type** — card type (credit / debit)  
- **bank_name** — issuing bank name  
- **error_type** — payment error code for failed transactions  
- **currency** — transaction currency (USD, EUR)  
- **card_country** — issuing bank country code  

---

## Project Goal
The goal of this project was to analyze a **payment domain dataset** in order to:
- identify patterns of **failed vs successful transactions**
- detect **payment anomalies**
- understand **user behavior**
- provide **business recommendations** to reduce payment failures and improve revenue stability

---

## Tools & Technologies
- **Python (Pandas, NumPy)** — data cleaning & EDA  
- **Tableau** — interactive dashboards  
- **Google Colab** — analysis environment

---

## Repository Structure
- `Payment_Analysis.ipynb` — data cleaning, exploratory data analysis (EDA) and feature preparation  
- `Tableau.twb` — Tableau workbook used to build the interactive dashboard  
- `dashboard.png` — preview image of the Tableau dashboard  
- `Payment_presentation.pdf` — project presentation with insights and recommendations  
- `payments_data.csv` — original dataset used for the analysis (566k+ transactions)
