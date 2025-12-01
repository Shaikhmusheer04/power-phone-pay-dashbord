# power-phone-pay-dashbord# 📊 PhonePe Transaction Analysis Dashboard

This repository contains an interactive Power BI dashboard that visualizes and analyzes financial transactions across different PhonePe services. The dashboard provides insights into total amounts, transaction volumes, success and failure rates, and reasons for failed transactions.

---

## 📌 **Project Overview**

The PhonePe Transaction Analysis Dashboard is designed to help users understand transaction patterns across different services such as:

* **Insurance**
* **Loans**
* **Money Transfer**
* **Recharge & Bills**

The dashboard uses multiple visualizations to track performance, detect anomalies, and provide a detailed overview of user behavior and payment issues.

---

## 📅 **Date Range Filtering**

A slicer allows selectable date ranges. In the screenshot example, the range used is:

* **1/1/2024 to 12/30/2024**

Users can dynamically filter all visuals based on selected dates.

---

## 🧮 **Key Metrics Displayed**

The top KPIs include:

* **Total Amount:** 3,333M
* **Successful Transactions:** 288K
* **Total Transactions:** 300K
* **Failed Transactions:** 12K

These metrics give an instant summary of platform performance.

---

## 📊 **Visualizations Included**

### **1. Services vs Amount (Bar Chart)**

Shows total transaction amount contributed by each service category:

* Loans
* Insurance
* Money Transfer
* Recharge Bills

### **2. Failed Payment Reasons (Pie Chart)**

Highlights common failure causes such as:

* Server Error
* Wrong PIN
* Insufficient Balance
* Wrong Info
* Bank Denied

Includes percentage breakdown for each reason.

### **3. Month vs Amount (Line Chart)**

Displays monthly transaction amount trends to observe growth patterns, seasonal spikes, or drops.

---

## 🗂️ **Data Sources Used**

The report is built using the following data tables:

* `All_Transactions`
* `All_Users`
* `Insurance`
* `Loans`
* `Money_Transfer`
* `Recharge_Bills`

---

## 🛠️ **Tools & Technologies**

* **Power BI Desktop** for building and designing the dashboard
* **DAX** for custom measures
* **Power Query** for data cleaning and transformation

---

## 📁 **Repository Contents**

* `.pbix` file of the dashboard
* README file describing the project
* Dataset files (optional based on upload)

---

## 🚀 **How to Use**

1. Clone or download the repository.
2. Open the `.pbix` file in **Power BI Desktop**.
3. Interact with filters and visuals to explore insights.



