WEEK 1 - UNDERSTANDING THE BUSINESS PROBLEM
E-COMMERCE ORDER MANAGEMENT DATABASE SYSTEM
============================================

OVERVIEW
--------
This folder contains the Week 1 deliverables for the E-Commerce Order Management
Database System semester project. The objective of this phase is to analyze the
business requirements of an e-commerce platform and document them in a structured
Software Requirement Specification (SRS) that will guide the database design in
later weeks (ER modeling, normalization, SQL implementation, and reporting).

BUSINESS SCENARIO
-----------------
A rapidly growing e-commerce company needs a centralized database to manage
customer registration, product and category management, supplier and inventory
tracking, order processing, payment management, shipment tracking, and customer
reviews - reducing data redundancy and enabling accurate business reporting.

CORE ENTITIES USED
-------------------
The project uses the following ten mandatory entities throughout the semester
(no entities or attributes are added, removed, or renamed):

1. Customer       - Customer ID, Name, Email, Mobile Number, Address, Registration Date
2. Category       - Category ID, Category Name, Description
3. Product        - Product ID, Product Name, Price, Stock Quantity, Category ID
4. Supplier       - Supplier ID, Supplier Name, Contact Information
5. Order          - Order ID, Customer ID, Order Date, Total Amount, Order Status
6. Order Details  - Order Detail ID, Order ID, Product ID, Quantity, Unit Price
7. Payment        - Payment ID, Order ID, Payment Method, Payment Date, Payment Status
8. Shipment       - Shipment ID, Order ID, Delivery Address, Shipment Date, Delivery Status
9. Review         - Review ID, Customer ID, Product ID, Rating, Comments

FOLDER CONTENTS
----------------
Week1/
    Requirement_Analysis_Report.pdf     - Business scenario, entity purposes, processes, stakeholders
    Business_Requirement_Document.pdf   - Functional & non-functional requirements, scope, assumptions/constraints
    SRS_Document.pdf                    - Formal Software Requirement Specification
    README.txt                          - This file

DOCUMENT SUMMARIES
-------------------

Requirement_Analysis_Report.pdf
    Analyzes the business scenario, explains the purpose of each core entity,
    identifies the major business processes, and profiles the system's
    stakeholders and their roles.

Business_Requirement_Document.pdf
    Lists detailed functional requirements (by module: customer, product/category,
    supplier, order, payment, shipment, review, reporting) and non-functional
    requirements (performance, scalability, security, integrity, etc.), defines
    the project scope (in-scope / out-of-scope), and states the assumptions and
    constraints.

SRS_Document.pdf
    Consolidates the above into a standard SRS format: introduction (purpose,
    scope, audience, definitions), overall description, data model overview,
    functional and non-functional requirements, external interface requirements,
    and assumptions/dependencies/constraints.

HOW TO USE THIS REPOSITORY
----------------------------
1. Review Requirement_Analysis_Report.pdf first to understand the business context.
2. Review Business_Requirement_Document.pdf for the detailed requirement lists.
3. Review SRS_Document.pdf for the consolidated, formal specification used as the
   baseline for subsequent design phases.

PROJECT ROADMAP (BEYOND WEEK 1)
---------------------------------
This requirement analysis feeds directly into later phases of the project:
ER diagram design -> normalization -> SQL schema implementation -> sample data ->
query/report generation.

AUTHOR
------
Prepared as part of a Database Analyst semester project assignment
(Week 1 deliverable).
