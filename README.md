# Expense Management System Automation

## 📌 Project Name
**Expense Management System - Selenium Automation**

## 🎯 Objective
To automate the process of logging into the CRM Expense Portal and creating a new expense entry, including:
- Date selection
- Dropdown interactions
- File uploads
- Form submissions

Using **Selenium WebDriver with Java**.

---

## 🛠️ Tools & Technologies

| Category              | Tool/Technology         |
|-----------------------|-------------------------|
| Language              | Java                    |
| Automation Tool       | Selenium WebDriver      |
| Browser               | Chrome                  |
| Driver Management     | WebDriverManager        |
| IDE                   | Eclipse / IntelliJ IDEA |

---

## ✅ Pre-requisites
- JDK installed and configured  
- Chrome browser installed  
- WebDriverManager to manage ChromeDriver  
- Eclipse or IntelliJ for Java development

---

## 🚀 Test Execution Flow

### 🔹 Step 1: Launch Browser & Open CRM URL
- Launch Chrome using WebDriverManager  
- Navigate to: `https://crmexp.*****.com/login`

### 🔹 Step 2: Login to Application
- Enter email: `rohan.****h@*****.com`  
- Enter password: `*****@*******`  
- Click the **Login** button

### 🔹 Step 3: Navigate to Add Expense Page
- Click on **"Add New Expense"** using JavaScriptExecutor

### 🔹 Step 4: Fill Trip Details (Form 1)
- Select **Trip Start Date**: `15th`  
- Select **Trip Completion Date**: `20th`  
- Choose **Trip Member**: `Rutvik Sharma`  
- Select **Client**: `HH. (CLT-2025-000032)`  
- Enter **Purpose of Trip**: `Client Visit to Delhi Office`  
- Enter **Trip Description**: `Attending 3-day client strategy meeting in Delhi.`  
- Select **Team Lead**: `Mahesh Makwana`  
- Select **Project Manager**: `Alok Sahijwani`  
- Click **Save & Continue**

### 🔹 Step 5: Fill Expense Table Entry (Form 2)
- Select **Date**: `05-07-2025`  
- Select **Time Slot**: `06:00 - 12:00`  
- Select **Category**: `Fuel`  
- Select **Sub-category**: `Diesel`  
- Enter **Description**: `Meeting`  
- Enter **Amount**: `1500`  
- Select **Payment Mode**: `Paid By Company`  
- Select **Trip Member**: `Rohan Parekh`  
- Select **Client**: `HH. (CLT-2025-000032)`  
- Enter **Location**: `Mumbai`  
- Enter **Note**: `Project meeting notes`  
- Upload PDF File: `ahmedabad-dwarka.pdf`

### 🔹 Step 6: Submit Form
- Click the **Save** button to add the expense entry

### 🔹 Step 7: Close Browser
- Use `driver.close()` to end the session

---

## 🧪 Author
**Harshal Oza**  
_Manual + Automation Tester | Selenium | Java | TestNG | WebDriverManager | Custom Frameworks_
