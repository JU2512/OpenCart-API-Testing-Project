# OpenCart API Automation Testing Project

A complete **API Testing & Automation Project** for OpenCart focused on validating core eCommerce cart workflows using **Postman + Newman** with dynamic request chaining, automated assertions, and HTML reporting.

---

# Project Objective

To design, test, and automate end-to-end OpenCart API workflows by validating authentication, cart operations, request chaining, and business logic through structured API testing practices.

---

# Scope of Testing

This project covers the complete cart lifecycle through OpenCart APIs:

* API Login Authentication
* Generate API Token
* Add Product to Cart
* Retrieve Cart Products
* Update Product Quantity
* Remove Product from Cart
* Validate Cart Status After Each Operation

---

# Tools & Technologies Used

* Postman
* Newman
* JavaScript (Postman Test Scripts)
* OpenCart API
* GitHub
* HTML Reporting

---

#  Key Features

## Dynamic Request Chaining

* `api_token` captured after login
* `cart_id` dynamically stored and reused
* Environment variable management

## Automated Assertions

* Status code validation
* Success message validation
* Product count verification
* Cart total verification
* Quantity update validation

## Reporting

* Newman CLI execution
* HTML report generation for execution summary
* Debugging through real API response analysis

---

#  Workflow Covered

### Step 1: Login API

* Authenticate using username & API key
* Capture `api_token`

###  Step 2: Add Product to Cart

* Add product dynamically using token

### Step 3: Get Cart Products

* Validate product added successfully
* Store cart product key

###  Step 4: Update Product Quantity

* Modify product quantity
* Validate update flow

###  Step 5: Remove Product

* Delete product from cart

###  Step 6: Final Cart Validation

* Confirm cart is empty

---

#  Repository Contents

* OpenCart Postman Collection (`OpenCart-E2E.json`)
* Environment File (`QA.postman_environment.json`)
* Newman HTML Report
* Screenshots (optional)
* Project Documentation

---

#  Skills Demonstrated

* API Testing
* API Automation
* Postman Collection Design
* Newman Execution
* JavaScript Assertions
* Environment Variables
* Request Chaining
* Debugging & Response Validation

---

# Sample Newman Command

```bash id="q0obzg"
newman run OpenCart-E2E.json -e QA.postman_environment.json -r cli,html --reporter-html-export report.html
```

---

#  Key Learning Outcome

Through this project, I gained practical experience in:

* Real-world API workflow validation
* Dynamic variable handling
* Automation execution
* Assertion debugging
* Business logic testing
* Professional API documentation

---

# Final Outcome

Successfully automated OpenCart’s cart workflow and built a reusable API automation project that simulates real-world QA testing practices.

---

# About Me

I’m actively building practical projects in **API Testing, Manual Testing,Automation Testing and Software Quality Assurance** to strengthen my QA career.

---

**Created by:** Jyothi Urade
**Role:** API Tester | QA Learner | Manual Tester
