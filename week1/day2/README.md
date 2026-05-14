-> Day 2 - Salesforce Platform Basics

-> What is Salesforce Platform?

Salesforce Platform is a cloud-based platform that helps businesses manage customer relationships and build applications without managing servers or infrastructure.

It provides:
- CRM functionality
- Custom application development
- Automation tools
- Security features
- Reporting and dashboards
- APIs for integration

Salesforce uses **multi-tenant architecture**, which means multiple organizations share the same infrastructure while keeping their data secure and separate.

-> Core Concepts

-> 1. App

An App in Salesforce is a collection of tools, objects, tabs, and features grouped together for a specific business process.

Example:
Sales App
- Leads
- Accounts
- Contacts
- Opportunities

Users switch between apps using the App Launcher.

-> 2. Object

Objects are database tables used to store data.

Standard Objects:
- Account
- Contact
- Opportunity
- Lead

Custom Objects:
- Student
- Course
- Patient
- Appointment

Each object contains:
- Records → rows
- Fields → columns

-> 3. Tab

Tabs allow users to access objects or pages from the navigation bar.

Examples:
- Accounts Tab
- Contacts Tab
- Reports Tab

Tabs make navigation easier for users.

-> Difference Between App and Object

App:
- An app is a collection of tools, tabs, and objects grouped together for a specific business purpose.
- It helps users navigate different features easily.
- An app can contain multiple objects.
- Example: Sales App, Service App

Object:
- An object is used to store data in Salesforce.
- It works like a database table.
- Objects contain records and fields.
- Example: Account Object, Contact Object

In simple terms:
App = Collection of features for users  
Object = Place where data is stored

-> Configuration vs Coding

Configuration (No Code / Clicks)

Used when business requirements can be solved using Salesforce’s built-in tools.

Examples:
- Creating validation rules
- Building workflows using Flow

Tools Used:
- Flow Builder
- Process Builder
- Validation Rules
- Page Layouts

Coding (Apex / Development)

Used when complex business logic is required.

Examples:
- Custom payment integration
- Complex approval process

Tools Used:
- Apex
- Lightning Web Components
- APIs
- Visualforce

-> How Developers Extend Salesforce

Developers extend Salesforce by using:

- Apex
- Lightning Web Components
- APIs
- Custom objects
- Custom apps

This helps organizations build solutions based on business needs.

-> System Design Example

College Management System

App Name:
College Management App

Objects:
- Student
- Faculty
- Course
- Attendance
- Exam
- Fee Payment

User Interaction:
- Students can view courses and results
- Faculty can update attendance
- Admin manages fees and records

-> How CRM Concepts Fit into Salesforce Platform

- Account → Company/Organization
- Contact → Individual person
- Opportunity → Sales deal
- Lead → Potential customer

These objects are grouped inside apps like the Sales App.

-> Multi-Tenant Architecture

Multi-tenant architecture means multiple businesses use the same Salesforce infrastructure.

Benefits:
- Lower cost
- Automatic updates
- Scalability
- Security

Example:
Like multiple tenants living in the same apartment building but each having separate apartments.

-> Trailhead Modules Completed

✅ Agentforce 360 Platform Basics 
<img width="1919" height="1061" alt="Screenshot 2026-05-11 192513" src="https://github.com/user-attachments/assets/63b8bb29-ecf1-4cdc-8e38-cd96a06e6fb6" />

By the end of Day 2, I learned:

- How Salesforce platform works
- Difference between App, Object, and Tab
- Configuration vs coding
- Multi-tenant architecture
- How developers extend Salesforce
- How CRM fits into Salesforce platform
