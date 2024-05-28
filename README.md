# The Bike Store Management System

# Overview
The Bike Store Management System is a comprehensive solution designed to meticulously catalog and manage day-to-day operations and sales activities within a dynamic cycling retail environment. In response to the growing demand for efficient store management and the need to analyze sales trends across various outlets, a dual-functional system that seamlessly integrates operational and analytical databases has been crafted.
The operational database serves as the backbone of the system, dedicated to recording and tracking the intricacies of daily transactions, inventory updates, and customer interactions. This functionality ensures a streamlined process for managing orders, stock levels, and overall store operations. With a focus on real-time data entry and retrieval, the operational database empowers store staff to efficiently navigate the daily challenges of running a bike store.
On the other hand, our analytical database plays a pivotal role in unraveling the broader narrative of the business. By harnessing the power of historical sales data, this component of the system enables stakeholders, particularly managers, to gain profound insights into sales trends over the years and across different store locations. The analytical database becomes a strategic tool for decision-making, providing a platform for managers to assess employee performance, identify top-selling products, and formulate informed strategies for business growth.
In essence, the Bike Store Management System is a sophisticated tandem of operational efficiency and analytical prowess, designed to elevate the management and performance evaluation processes within the dynamic realm of bicycle retail.
# 2. Data Sources:
- Mockaroo: https://www.mockaroo.com https://simplemaps.com/data/us-cities 
- US Cities Name Kaggle: https://www.kaggle.com/datasets/dillonmyrick/bike-store-sample-database
3. Application Design
  
The tools used during development includes Python, MySQL Workbench, PyQt Designer, ERD Plus and VSCode. It requires additional packages to be installed: <br>
• Pandas <br>
• Numpy <br>
• Matplotlib <br>
• PyQt5 and PyQt5-Tools <br>
• Seaborn <br>
• MySQL Connector for Python <br>
• SMTPLIB <br>
The application consists of two main modules: Operation Module and Analytical Module.

# Operation Module
Customers engaging with the Bike Store Operational Database can seamlessly register, log in, and initiate various transactions to enhance their shopping experience. Within this segment of the system, customers have the capability to place new orders, submit feedback, and raise any concerns through a streamlined complaints process. The Bike Store Operational Database stands as a user-centric hub, where customers, employees, and managers converge to optimize the entire spectrum of operations, from order placement to resolution management and strategic decision-making.

# Analytical Module
Within the Bike Store Analytical Database module, our focus revolves around leveraging the wealth of data accumulated from our operational database alongside external sources. This comprehensive analysis yields an insightful dashboard that delves into the intricacies of sales and operational performance. The dashboard provides a panoramic view of the store's landscape, encompassing diverse metrics such as sales performance, employee efficiency, and regional product dynamics. The dashboard facilitates an in-depth analysis of order-related metrics, including order counts by status, the year-wise spike of bike quantities by category, and overall order trends by year and month. For a regional perspective, users can assess total orders by region, identifying patterns and optimizing strategies based on regional demand.

# File Details


.ui file - Qt5 UI File <br>
.py file - Python <br>
.ipynb file - Python Jupyter Notebook <br>
.qrc file - Resource File Config <br>
.ini file - Python Config File <br>
.sql file - SQL Dump <br>

Following is the list of the files for this application. <br>
1     BikeStoreCustMainDialog.py           Customer Portal Dialog <br>
2     BikeStoreCustMainDialog.ui           Customer Portal Dialog <br>
3     BikeStoreCustMainDialog_ui.py        Customer Portal Dialog <br>
4     BikeStoreEmplMainDialog.py           Employee Portal Dialog <br>
5     BikeStoreEmplMainDialog.ui           Employee Portal Dialog <br>
6     BikeStoreEmplMainDialog_ui.py        Employee Portal Dialog <br>
7     BikeStoreMainWin.py                  Main Window (Login Page) <br>
8     BikeStoreMainWin.ui                  Main Window (Login Page) <br>
9     BikeStoreMainWin_ui.py               Main Window (Login Page) <br>
10    BikeStoreManagerDashDialog.py        Manager Dashboard Dialog <br>
11    BikeStoreManagerDashDialog.ui        Manager Dashboard Dialog <br>
12    BikeStoreManagerDashDialog_ui.py     Manager Dashboard Dialog <br>
13    BikeStoreManagerMainDialog.py        Manager Portal Dialog <br>
14    BikeStoreManagerMainDialog.ui        Manager Portal Dialog <br>
15    BikeStoreManagerMainDialog_ui.py     Manager Portal Dialog <br>
16    BikeStoreResetPwdDialog.py           Reset Password Dialog <br>
17    BikeStoreResetPwdDialog.ui           Reset Password Dialog <br>
18    BikeStoreResetPwdDialog_ui.py        Reset Password Dialog <br>
19    BikeStoreSignUpDialog.py             Sign Up Dialog <br>
20    BikeStoreSignUpDialog.ui             Sign Up Dialog <br>
21    BikeStoreSignUpDialog_ui.py          Sign Up Dialog <br>
22    BikeStoreUtils.py                    Utility File used in Application <br>
23    TerraBikes.ipynb                     Notebook used to Launch the Application <br>
24    resources.qrc                        QT Resources File <br>
25    resources_rc.py                      QT Resources Python File <br>
26    terrabikes.ini                       Database Config File (Operational) <br>
27    terrabikes_bi.ini                    Database Config File (Analytical) <br>
28    TerraBikes.py                        Alternate way to Launch <br>
29    terrabikes.sql                       Operational DB Dump <br>
30    terrabikes_bi.sql                    Analytical DB Dump <br>
 

  
