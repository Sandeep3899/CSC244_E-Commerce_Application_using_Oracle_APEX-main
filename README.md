# E-Commerce Application using Oracle APEX

## 📌 Overview
This project is an **E-Commerce Application** built using **Oracle Application Express (APEX)** and **Oracle Autonomous Database (ADB)**. The goal was to develop a **scalable, secure, and user-friendly** platform that efficiently manages orders, products, customers, and sales data. 

This project demonstrates the integration of **low-code development with Oracle APEX** to enable rapid application deployment while ensuring robust database management with Oracle Autonomous DB.

## 🚀 Features
- **User Authentication & Dashboard**
- **Product & Order Management**
- **Customer Data Management**
- **Data Visualization & Reporting**
- **SQL Workshop for Queries**
- **Interactive Analysis Reports**
- **CRUD Operations (Create, Read, Update, Delete)**
- **Seamless integration with Oracle Cloud**

## 🛠️ Technologies Used
- **Oracle APEX** (Frontend)
- **Oracle Autonomous Database (ADB)** (Backend)
- **SQL for Data Processing**
- **Oracle REST Data Services (ORDS)**
- **Cloud-based Database Hosting**


## 📊 Database Schema
The project follows a **relational database schema** with the following key entities:
- **Customers** (ID, Name, Email)
- **Stores** (ID, Name, Address, Contact)
- **Products** (ID, Name, Category, Price)
- **Orders** (ID, Customer, Store, Status)
- **Order Items** (Order ID, Product ID, Quantity)
- **Payments** (Order ID, Payment Type)
- **Reviews** (Order ID, Rating, Message)

## 📖 Dataset
We used a **real-world e-commerce dataset** from **[Olist Brazilian E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)**, which contains over **100K+ orders** placed across multiple marketplaces in Brazil between **2016-2018**.

## 🔍 Data Flow & Architecture
The application is structured using **Oracle APEX’s low-code environment** and is integrated with **Oracle Autonomous Database**, which ensures:
1. **Secure authentication & access control**
2. **Efficient handling of large-scale datasets**
3. **Automated performance tuning & backups**
4. **Data visualization using Oracle APEX's built-in tools**

## 🏗️ How to Set Up the Project
### Prerequisites:
- **Oracle Cloud Account** (For Oracle APEX & Autonomous DB)
- **SQL Developer** (Optional, for database management)

### Steps:
1. **Set up Oracle Autonomous Database on Oracle Cloud Infrastructure**
2. **Enable Oracle APEX & ORDS for front-end development**
3. **Import dataset into Oracle APEX using the Data Upload Wizard**
4. **Configure database schema and relationships**
5. **Build interactive web applications using APEX App Builder**
6. **Deploy and test the e-commerce functionalities**

## 🔮 Future Enhancements
- Implement **Machine Learning-based sales forecasting**
- Add **Personalized Product Recommendations**
- Enhance UI/UX with **custom styling & components**
- Improve **security measures for payment handling**

## 📜 Contributors
- **Sandeep Reddy Yeruva**
- **Rajasekhar Reddy Kolagotla**
- **Chanakya Rudhra Baluguri**

## 📝 References
- [Oracle APEX Documentation](https://docs.oracle.com/en/database/oracle/application-express/index.html)
- [Oracle Autonomous Database](https://docs.oracle.com/en/cloud/paas/autonomous-database/index.html)
- [Oracle SQL Developer Web](https://docs.oracle.com/en/database/oracle/sql-developer-web/index.html)
- [Olist E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

🔹 *This project was developed as part of CSC 244 – Database System Design (Fall 2023) at California State University, Sacramento.*

