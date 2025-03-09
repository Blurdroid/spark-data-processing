# Data Processing and Analysis using Spark | Spark Project-1  

## 📌 Overview  
This project demonstrates how to perform **data processing and analysis** using **Apache Spark** on a **relational database**. We use **Spark SQL** to perform **joins, aggregations, and transformations** on CSV-based datasets.  

## 📂 Dataset  
The project uses a **Retail Dataset** consisting of three tables:  
- `customers`  
- `orders`  
- `order_items`  

## 🔧 Tech Stack  
- Apache Spark  
- SQL  
- MongoDB  

## 🚀 Project Setup  
1. **Set up local spark**    
2. **Upload the dataset** in Databricks:  
   - Create a `Data` folder and upload the CSV files.  

## 🛠️ Steps to Process the Data  
### **1️⃣ Load Data and Create DataFrames**  
- Verify if the files are uploaded:  
  ```python
  %fs ls dbfs:/FileStore/tables/Data

