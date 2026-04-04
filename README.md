# Online Retail Customer Behavior Analytics

## Key Project Details

- Customers are grouped into four types: **Champions** (best), **Loyal**, **At Risk** (might leave), and **Hibernating** (already left).
- Track how many customers return month after month using **cohort analysis**.
- Find out which customers spend the most and which products sell best together.
- See which countries bring the most revenue.
- Get clear recommendations: who to reward, who to win back, and where to focus marketing.

---

## What is this project about?

We took real sales data from an online gift shop (UK-based, 2010–2011) and answered three simple questions:

1. Who are our best customers?
2. Who is about to stop buying from us?
3. How can we get them to buy again?

---

## Where is the data from?

**Source:** [UCI Machine Learning Repository – Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail)  
**Direct link:** https://doi.org/10.24432/C5BW33  

The dataset has **541,909 transactions** from December 2010 to December 2011.  
It includes: invoice number, product name, quantity, price, customer ID, and country.

---

## What did we do? (step by step, in plain words)

### Step 1 – Clean the data
- Removed orders without a customer ID
- Removed cancelled orders
- Kept only positive quantities (actual sales)

### Step 2 – Group customers into four types
We looked at three things for every customer:
- **How recently** they bought
- **How often** they buy
- **How much money** they spend

Then we split them into:

| Type | Meaning |
|------|---------|
| Champions | Buy often, recently, and spend a lot – our best friends |
| Loyal | Good, regular customers |
| At Risk | Used to buy a lot but have stopped recently – might lose them |
| Hibernating | Bought once long ago and never came back |

### Step 3 – Track how many customers come back
We followed each month’s new customers to see how many returned the next month.  
We made a heatmap called **“How Many Customers Come Back After Their First Purchase”**.

### Step 4 – Find best-selling products and product pairs
We listed the top 10 products sold.  
We also found which products are often bought together (so we can bundle them).

### Step 5 – Look at monthly sales
We plotted total sales per month to see seasonal peaks.

---

## What did we learn? (the story)

- **Only 20 to 40 out of every 100 new customers come back for a second purchase.**  
  Most people buy once and then disappear.

- **Champions are only 18% of all customers** but they bring most of the money.

- **At Risk customers are 24% of all customers** – they used to spend well but have gone quiet.  
  We can win them back.

- **Best-selling product:** *White Hanging Heart T-Light Holder* (a small decorative light)

- **Sales spike in November** – holiday shopping season.

---

## Tools we used

- **Python** (Pandas, Matplotlib, Seaborn) – for cleaning data, making charts, and analysis  
- **Power BI** – for the interactive dashboard  
- **Jupyter Notebook** – to write and run the code step by step  

---

## Project team

- Isha Patel  
- Sakshi Sharma
- Yashvi Soni  
- Rishi Kanadia  
