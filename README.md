# 🚀 LLM Powered SQL Generator and Executer

## 📝 Overview
This repository hosts a **LLM-powered SQL generator and executer** designed to convert **natural language queries** into **SQL statements** and execute them seamlessly. Users can retrieve data from their database simply by describing their query in everyday language, eliminating the need for manual SQL coding.

## ✨ Features
✅ **Natural Language to SQL**: Converts human-readable queries into valid SQL.  
✅ **Automated SQL Execution**: Runs the generated SQL on the connected database.  
✅ **Intelligent Query Optimization**: Ensures efficiency and accuracy in SQL generation.  
✅ **User-Friendly Interface**: Intuitive design for ease of use.  

## 🖼️ Image Preview

![image](https://github.com/user-attachments/assets/d2118892-5b0c-475b-af91-3ab37e074bff)

The image showcases the tool's interface where a user enters a query:  
*"customer with highest order value and the product."*

The system automatically generates and executes the following **SQL query**:
This query efficiently retrieves the **customer with the highest order value and the associated product**. 🛒💰

The output table displays:
- 🆔 **Customer ID**
- 👤 **Name**
- 📧 **Email**
- 📞 **Phone**
- 📍 **City**
- 📦 **Product Name**
- 💵 **Total Order Value**

Example result:
```
customer_id | name          | email              | phone         | city       | product_name | total_order_value
------------|--------------|--------------------|--------------|------------|--------------|------------------
1           | Alice Johnson | alice@example.com | 123-456-7890 | Amsterdam  | Laptop       | 1199.98
```

## 🚀 Getting Started
### 🔧 Installation
Clone the repository:
```bash
git clone https://github.com/BrainyyMachines/LLMPoweredSQLGenerator.git
```
Install dependencies:
```bash
pip install -r requirements.txt
```

### ▶️ Usage
Run the application:
```bash
streamlit run main.py
```
Enter a natural language query, and the system will return structured SQL and execute it.

## 🤝 Contributing
Contributions are **welcome**! 🎉 Please **open an issue** or submit a **pull request**.

## 📜 License
This project is licensed under the **MIT License**. 🔓


