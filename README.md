# 🧪 QA Fox Automation Project

This project is designed to automate various scenarios for the **TutorialsNinja** application and advanced Selenium use cases like multi-window handling, alerts, file uploads/downloads, form validation, and more.

It is built using **Java**, **Selenium WebDriver**, and **TestNG**, following best practices for test automation.

---

## 📂 Directory Structure

~~~
└── kartiksharma200-qafox-automation-project/
    ├── README.md
    ├── pom.xml
    ├── testng.xml
    └── src/
        └── test/
            └── java/
                ├── HandleMultiTabWindow/
                │   ├── FileUploadDownload.java
                │   ├── FormSubmitAndValidation.java
                │   ├── handleAlertwithPoP.java
                │   ├── handleBrokenLink.java
                │   ├── HandletabAndWindow.java
                │   └── MouseKeyboardAction.java
                └── TutorialNinja/
                    ├── BaseTest.java
                    ├── Cart.java
                    ├── checkout.java
                    ├── ExcelUtils.java
                    ├── Login.java
                    ├── Register.java
                    ├── search.java
                    ├── shoppingcart.java
                    └── wishlist.java
~~~

---

## ✅ Features Covered

### 🔹 TutorialNinja Test Suite
- User registration & login
- Product search & wishlist
- Shopping cart and checkout flow
- Data-driven testing using ExcelUtils

### 🔹 Advanced Selenium Features
- Handling multiple windows and browser tabs
- Mouse and keyboard actions using `Actions` class
- Handling alerts and pop-ups
- File upload and download
- Form validations
- Broken link validation

---

## 🚀 How to Run the Project

1. **Clone the Repository**
```bash
git clone https://github.com/kartiksharma200/qafox-automation-project.git
cd qafox-automation-project
```
2. **Install Dependencies**

```bash
mvn clean install
```
3. **Execute TestNG Suite**
```bash
mvn test -DsuiteXmlFile=testng.xml
```
## 🛠️ Tools & Technologies
- Java
- Selenium WebDriver
- TestNG
- Apache POI (for Excel reading)
- Maven

## 📌 Prerequisites
- Java JDK 8 or higher
- Maven 3.6+
- TestNG plugin in IDE
- Chrome or other browser drivers added to system path

## 📧 Contact
- Author: Kartik Sharma
- LinkedIn: linkedin.com/in/kartiksharma200
- Email: Kartikgautam1106@gmail.com

## 📝 License
This project is licensed under the MIT License.
