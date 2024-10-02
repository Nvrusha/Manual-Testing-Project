# 🛒 OpenCart E-commerce Project

This repository demonstrates my manual testing expertise through the OpenCart e-commerce platform, an open-source online store management system. The project is focused on ensuring the robustness and quality of key e-commerce functionalities, including product management, order processing, customer workflows, and seamless API/database interactions. It aims to simulate real-world scenarios, ensuring that users can navigate and complete purchases smoothly without encountering bugs or issues.

# 📋 Project Overview:

## 🎯 Objective
The primary objective of this project is to conduct thorough manual testing of OpenCart’s key modules to identify any functional issues, ensure stable performance, and guarantee that customer transactions are error-free. This includes evaluating both front-end and back-end processes, ranging from user registration to order fulfillment, as well as testing the integration of APIs and database transactions.

By focusing on multiple types of testing—functional, regression, API, and database testing—this project not only covers basic user interactions but also ensures data integrity and proper backend functionality.

## 🔍 Scope
### This project comprehensively tests all core features of the OpenCart platform, including but not limited to:

1. 👥 User registration and login processes.
2. 🔍 Product search and filter functionality, ensuring users can easily find items.
3. 🛒 Cart functionality including adding, updating, and removing products from the cart.
4. 💳 Checkout process covering payment methods, shipping options, and order confirmation.
5. 📜 Order history and user profile management features.

### Additional focus was placed on:
- **⚙️ Admin Panel Testing:** Testing the admin capabilities, such as product management, customer management, and reporting tools.
- **🔗 Third-party Integrations:** Validating the proper functioning of APIs for payment gateways, shipping services, and other external systems.

## 🔧 Testing Methodologies:
### 1. ⚙️ Functional Testing:
Functional testing was carried out to verify that every feature of the OpenCart platform works as intended. This involved:
- Ensuring all links, buttons, and user interface elements were operational.
- Testing each user scenario from browsing products to completing a purchase.
- Verifying error handling for invalid inputs or failed transactions.

### 2. 🔄 Regression Testing:
Performed regularly after any code updates or configuration changes to ensure no new defects were introduced. It confirmed the system’s stability by retesting previously functional areas to ensure their continued proper operation.

### 3. 🔌 API Testing
I have focused on testing the Register and Login API endpoints using Postman to validate the platform's user authentication process. This involved:
- Verifying successful user registration and login attempts.
- Ensuring proper error handling for invalid credentials and duplicate registrations.
- Testing the responses for correct status codes, response times, and returned data.

### 4. 🗄️ Database Testing
I conducted database testing to ensure data accuracy and integrity in MySQL. This involved:
- Verifying the correct insertion of new user registration data.
- Ensuring consistency in login attempts and session management.
- Testing for data accuracy across related tables.

## 🛠 Tools
### 🛠️ Postman:
Used for API testing, focusing on user registration and login processes.

### 🐞 JIRA:
Used for tracking bugs, maintaining detailed records of defect reports, and managing the testing process.

### 🗄️ MySQL:
Used for database testing to verify the accuracy of data storage and retrieval, ensuring data integrity across user, product, and order tables.

## 📝 Bug Reporting & Test Documentation:
- All test cases and defect logs were created and maintained in JIRA, providing comprehensive documentation for the testing process.
- Detailed defect reports included information on how to reproduce the issue, the affected module, and severity level (critical, major, minor).
- Suggestions for performance improvements and user experience enhancements were also provided where applicable.

## 🌟 Key Outcomes:
- **🛠 Critical Bugs Identified:** Multiple critical bugs were identified, including issues with login functionality, incorrect user session management, and registration errors.
- **🚀 Performance Enhancements:** Recommendations were made to improve platform performance and optimize user interactions to reduce cart abandonment.
- **🔒 Improved Stability:** The testing process helped ensure the overall stability of the platform, resulting in smoother user experience, fewer defects, and enhanced integration with external systems.
- **📈 Increased Confidence in Release Quality:** By identifying defects early and conducting thorough regression testing, I contributed to a more reliable and high-quality product release.

## 🏃 How to Run the Tests:
- **🛠 Set Up OpenCart:** Download and install OpenCart on a local or test environment, ensuring all necessary dependencies are in place.
- **📄 Access Test Cases:** Review the detailed test cases provided in the repository to understand the scope and steps for manual testing.
- **✅ Execute Manual Tests:** Perform the manual tests as per the test cases, simulating real-world user scenarios such as product searches, order placements, and user profile management.
- **🔌 Run API Tests:** Use Postman to execute API tests for the registration and login processes. Ensure that the API responses are accurate, timely, and properly formatted.
- **🗄️ Verify Database Transactions:** Use MySQL to inspect the database for each user interaction and ensure proper data storage and retrieval. Test database queries to validate data integrity.
