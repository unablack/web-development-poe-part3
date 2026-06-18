# UNA Store – Web Development Project of Evidence (WEDE6021)

## Project Information

**Project Name:** UNA Store
**Module:** WEDE6021 – Web Development
**Institution:** Rosebank College
**Project Type:** Clothing Store Web Application
**Developers:**

* Muthivhi Unarine
* Sedzani Siaruli Precious

---

# Project Overview

UNA Store is a web-based clothing store application developed as part of the WEDE6021 Project of Evidence (POE). The system provides an online platform where customers can browse clothing products, register accounts, login securely, add products to a shopping cart, and complete purchases.

The application also includes administrative functionality for managing users, clothing products, seller requests, and customer orders. In addition, sellers can submit requests to sell clothing items through the platform, allowing administrators to review and manage submissions.

The project was developed using PHP, MySQL, HTML, CSS, and PHPMyAdmin.

---

# Features

## Customer Features

* User Registration
* User Login and Authentication
* Password Hashing and Verification
* Browse Clothing Products
* Add Products to Shopping Cart
* Update Cart Quantities
* Remove Products from Cart
* Continue Shopping
* Checkout System
* View Purchase History

## Seller Features

* Submit Seller Requests
* Provide Clothing Brand Information
* Submit Clothing Descriptions
* Submit Clothing Image References

## Administrator Features

* Administrator Login
* View Customer Orders
* Manage Seller Requests
* Verify Customer Registrations
* Add Clothing Products
* Update Clothing Products
* Delete Clothing Products
* Manage Customer Accounts

---

# Technologies Used

### Front-End

* HTML5
* CSS3

### Back-End

* PHP

### Database

* MySQL
* PHPMyAdmin

### Development Environment

* XAMPP

---

# Database Information

**Database Name:**

```text
una_store
```

The database contains the following tables:

```text
tbladmin
tblclothes
tblorder
tblorderline
tblsellerrequest
tbluser
```

---

# Installation Instructions

## Step 1: Install XAMPP

Download and install XAMPP:

https://www.apachefriends.org/

Start:

* Apache
* MySQL

from the XAMPP Control Panel.

---

## Step 2: Import Database

1. Open phpMyAdmin.

```text
http://localhost/phpmyadmin
```

2. Create a database called:

```text
una_store
```

3. Import:

```text
myClothingStore.sql
```

located in the Database folder.

---

## Step 3: Place Project Files

Copy the UNA Store project folder into:

```text
C:\xampp\htdocs\
```

Example:

```text
C:\xampp\htdocs\UNAStore
```

---

## Step 4: Run the Application

Open a browser and navigate to:

```text
http://localhost/UNAStore
```

---

# Default Administrator Account

Use the administrator account stored in the database.

If required, administrator credentials can be viewed directly within the tbladmin table in phpMyAdmin.

---

# Folder Structure

```text
UNAStore/

├── Database/
│   ├── myClothingStore.sql
│   ├── userData.txt
│   ├── clothesData.txt
│   ├── adminData.txt
│
├── Documentation/
│   ├── ERD.pdf
│   ├── TableStructures.docx
│   ├── Muthivhi_Unarine_Reflection.docx
│   ├── Sedzani_Siaruli_Precious_Reflection.docx
│
├── SourceCode/
│   ├── DBConn.php
│   ├── createTable.php
│   ├── loadClothingStore.php
│   ├── login.php
│   ├── register.php
│   ├── products.php
│   ├── cart.php
│   ├── checkout.php
│   ├── adminLogin.php
│   ├── adminMenu.php
│   └── other project files
│
├── Video/
│   └── Demonstration.mp4
│
└── README.md
```

---

# Demonstration Video

A complete demonstration video showing the functionality of the system can be viewed at:

**YouTube Link:**

```text
[INSERT YOUTUBE VIDEO LINK HERE]
```

The demonstration includes:

* User Registration
* User Login
* Form Validation
* Administrator Login
* User Verification
* Product Browsing
* Shopping Cart Functionality
* Seller Requests
* Order Processing
* Database Integration
* Source Code Demonstration

---

# Testing

The application was tested to ensure:

* Successful database connectivity
* User authentication functionality
* Administrator functionality
* Shopping cart operations
* Seller request submission
* Order creation and management
* Data retrieval from MySQL database

---

# Future Improvements

Potential future enhancements include:

* Online payment gateway integration
* Email notifications
* Product search functionality
* Product filtering and categories
* Image upload support
* Enhanced security controls
* Mobile-responsive design
* Customer reviews and ratings

---

# Declaration

This project was developed for academic purposes as part of the WEDE6021 Web Development Project of Evidence at Rosebank College.

All code, documentation, and supporting materials were created by the project team in accordance with the module requirements.

---



