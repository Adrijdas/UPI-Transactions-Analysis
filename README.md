# UPI Transactions Dashboard

**Real-Time Analytical Overview of Unified Payments Interface (UPI) Transactions**

![Dashboard Preview](Dashboard_Picture.png)

---

## Project Overview

The **UPI Transactions Dashboard** is an interactive analytical solution built in Microsoft Excel. It provides a comprehensive, real-time overview of UPI payment transactions across multiple dimensions such as geography, time, banking partners, UPI apps, merchant categories, and user demographics.

The dashboard is powered by a large-scale dataset containing **6 lakh+ rows** of transactional data. It transforms this raw data into clear, actionable insights that support operational monitoring, risk management, and business decision-making.

---

## Objectives

- Provide a single-pane real-time view of UPI transaction performance
- Track key performance indicators including volume, value, success rate, cashback, and fraud
- Enable interactive filtering by City, Gender, Merchant Name, and Merchant Category
- Analyze market share across major UPI applications
- Identify top-performing states, banks, and transaction types
- Uncover temporal patterns using daily trends, hourly distribution, and day-of-week heatmaps
- Highlight potential fraud cases for further investigation

---

## Dataset

| Attribute              | Details                          |
|------------------------|----------------------------------|
| **Total Rows**         | 6,00,000+                        |
| **Domain**             | Digital Payments / FinTech (UPI) |
| **Key Fields**         | Transaction ID, Amount, Date, Time, City, State, Gender, Bank, UPI App, Merchant, Category, Status, Cashback, Fraud Flag |
| **Scope**              | Multi-city, multi-bank, multi-app UPI transactions across India |

The dataset covers a wide range of real-world UPI activity including Person-to-Merchant (P2M), Person-to-Person (P2P), bill payments, online shopping, recharges, and more.

---

## Key Performance Indicators (KPIs)

| Metric                  | Value          | Description                                      |
|-------------------------|----------------|--------------------------------------------------|
| **Total Transactions**  | 5,02,887       | Total number of UPI transactions processed       |
| **Total Amount**        | ₹ 44.25 Cr     | Aggregate transaction value                      |
| **Total Cashback**      | ₹ 34.63 L      | Cashback amount distributed to users             |
| **Success Rate**        | 91.00%         | Percentage of successfully completed transactions|
| **Suspected Fraud**     | 17,089         | Transactions flagged as potentially fraudulent   |

---

## Dashboard Components

### Interactive Filters (Slicers)
- **City** – Hubli, Hyderabad, Indore, Jabalpur, Jaipur, Jodhpur, Kanpur, Kochi, Kolkata, Kota, Kozhikode, Lucknow, Madurai, Mangalore, Mumbai, and others
- **Gender** – Female / Male
- **Merchant Name** – Courier, Credit Card Bill, Games, Data Tutorial, DMart, Dominos, Electricity Board, etc.
- **Merchant Category** – Credit Card Bill, Education, Electricity Bill, Entertainment, Financial Services, Food & Dining, Fuel, Grocery, and more

### Visualizations

| Visualization                              | Insight Provided                                              |
|--------------------------------------------|---------------------------------------------------------------|
| Transactions Amount Over Time (Daily)      | Daily trend of transaction value                              |
| Transactions by UPI App                    | Market share of PhonePe, Google Pay, Paytm, Amazon Pay, BHIM, Cred Pay, WhatsApp Pay |
| Transactions by Status                     | Success / Failed / Pending / Refunded distribution            |
| Transactions Amount by State               | Geographic performance with India map and state ranking       |
| Transactions Amount by Bank                | Leading banks: HDFC, SBI, Kotak, Canara, ICICI, Axis, BoB, PNB |
| Transactions Amount by Transaction Type    | P2M, P2P, Bill Payment, Online Shopping, Recharge, Subscription, Wallet Transfer |
| Transactions Amount by Hour                | Peak transaction hours throughout the day                     |
| Transactions Amount by Hour & Day (Heatmap)| Weekly patterns and high-activity time slots                  |

---

## Key Insights

- **PhonePe** dominates the UPI app landscape with **45.75%** share, followed by Google Pay (**21.31%**) and Paytm (**14.34%**).
- **Maharashtra** leads in transaction value among all states.
- **HDFC Bank** processes the highest transaction amount among banks.
- **P2M (Person-to-Merchant)** transactions contribute the largest share of value.
- Transaction activity rises steadily through the day and **peaks in the evening hours**.
- The heatmap reveals clear differences between weekday and weekend usage patterns.
- Overall success rate stands strong at **91%**, while **17,089** transactions are flagged as suspected fraud for further review.

---

## Tools & Technologies

| Tool / Technology       | Purpose                                      |
|-------------------------|----------------------------------------------|
| Microsoft Excel         | Data modeling, calculations & dashboard UI   |
| Pivot Tables & Charts   | Interactive visualizations & aggregations    |
| Slicers                 | Dynamic multi-dimensional filtering          |
| Conditional Formatting  | Visual highlighting of key metrics           |

---

## Business Value

- **Operations Teams** → Monitor success rates and failed transactions in near real-time
- **Risk & Fraud Teams** → Quickly identify anomalous volumes and investigate flagged cases
- **Product & Partnership Teams** → Understand app-wise and merchant-category performance
- **Leadership** → Get a clear visual summary of UPI ecosystem health and growth trends

---

## Author

**[Adrij Das]**  
Data Analyst

---

## License

This project is open for educational and non-commercial use.  
Feel free to fork, modify, and enhance it.

---

**If you found this project useful, please give it a ⭐**
