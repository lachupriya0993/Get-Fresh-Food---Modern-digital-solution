
GetFreshFood – User Requirement Specification (URS)

This repository contains the User Requirement Specification (URS) created for GetFreshFood (GFF) as part of the  course project. The purpose of this document is to define the requirements for a proposed supermarket automation system that improves operational efficiency, data accuracy, and customer experience.

The URS captures the complete set of business, user, functional, and non-functional requirements derived from interviews with GFF stakeholders including cashiers, branch managers, promoters, storemen, and customers.

Project Overview

GetFreshFood currently operates using highly manual and repetitive processes: handwritten price tags, manual checkout, manual stock updates, and end-of-day reports done in Excel. These inefficiencies cause delays, errors, and poor customer experience.

Our proposed solution introduces a digitally integrated supermarket system with automated checkout, centralized product data, approval workflows, and an online shopping platform.

This URS document outlines all requirements needed to support this solution.

Goals and Objectives

Automate and streamline supermarket operations

Reduce manual data entry for cashier, promoter, and storeman roles

Improve data accuracy across pricing, stock, and sales records

Enable real-time visibility of product, inventory, and sales information

Provide structured approval workflows for stock and damaged goods

Introduce online shopping and delivery capabilities

Improve customer experience with faster, more reliable checkout

Project Scope
In Scope

Centralized Product Information System
Unified database for pricing, stock levels, and product details across all user roles.

Digital Checkout with Barcode Scanning
Automated checkout, receipt generation, refunds, and shelf label updates via E-ink labels.

Approval Workflows
Formal system for stock replenishment, damaged goods collection, and expired goods handling.

Real-Time Dashboards and Automated Reports
Updated insights for sales, stock alerts, and operational performance.

Online Shop & Home Delivery Website
Web-based shopping, synchronized with centralized product data.

Out of Scope

Supplier system integration

Mobile application development

HR allocation or staff training for new platforms

Loyalty points, vouchers, and promotional systems

User Research
User Persona

A cashier persona highlights major pain points such as manual checkout, repeated data entry, long queues, and slow reporting.

Customer Journey Map

Mapped across four stages to identify operational bottlenecks and opportunities for digital improvements.

User Stories

User stories were created for all major stakeholders:

Cashiers (checkout, refunds, daily reports)

Storemen (stock updates, replenishment, damaged goods handling)

Promoters (product enquiries, replenishment requests)

Branch Managers (dashboard, approvals, report generation)

Customers (online shopping, browsing, delivery tracking)

Examples include:

"As a cashier, I want to scan product barcodes so that checkout is fast and accurate."

"As a storeman, I want real-time stock alerts so that I can reorder items before they run out."

"As a customer, I want to purchase products online so that I don’t have to visit the store."

Use Case Model

A complete use case diagram is included in the URS, showing all interactions between:

Customer

Cashier

Branch Manager

Storeman

Promoter

Each actor’s key system interactions are documented to support workflow automation.

Functional Requirements
Activity Diagrams

Represent workflows for essential operations such as:

Starting a new transaction

Handling refunds

Maintaining product information

Updating warehouse stock

Online checkout & payment

Screen / Print-Out Designs

Prototype screens for cashier operations including:

Transaction search

Product lookup

Cart management

Payment selection windows

Non-Functional Requirements
User Volume

Expected number of users (branch manager, cashiers, storemen, promoters, customers) and usage frequency.

Business Transaction Volume

Estimated transaction counts for checkout, stock updates, online orders, reports, and approvals.

Data Volume

Retention policies and projected dataset sizes for:

Product forms

Transaction records

Reports

Online carts

Event logs

Security Requirements

Role-based access control for each data entity and business transaction.

Reliability

System availability

Downtime limits

Hardware recovery

Disaster recovery guidelines

Test Cases and Test Data

The URS includes detailed test cases for the “Start a New Transaction” workflow, covering:

Product search

Barcode scanning

Stock validation

Cart operations

Payment selection

Error messages

Total price calculation

Sample test data for products (ID, name, category, stock, price) is also provided.

Document Contents

The full URS includes the following sections:

Briefing of the Solution

Goals and Objectives

Scope (In/Out-of-Scope)

User Persona

Customer Journey Map

User Stories

Use Case Model

Functional Requirements

Non-Functional Requirements

Test Cases & Test Data

File Included

Team03_User_Requirement_Specification (1).pdf — Full URS document
