-> Day 3 - Data Modeling

-> What is Data Modeling in Salesforce?

Data modeling in Salesforce is the process of organizing business data in a structured way using objects, fields, records, and relationships.

It helps companies:
- Store data properly
- Maintain relationships between different data
- Avoid duplicate information
- Build scalable systems
- Improve data accuracy

Example:
In a college system, students, courses, faculty, and departments should be connected properly instead of storing everything in random spreadsheets.

-> Difference Between App, Object, Record, and Field

App:
- A collection of related tools, tabs, and objects
- Helps users perform specific business tasks
- Example: College Management App

Object:
- Stores data in Salesforce
- Works like a database table
- Example: Student Object

Record:
- A single entry inside an object
- Works like a row in a table
- Example: Student Name = John

Field:
- Stores specific information in a record
- Works like a column in a table
- Example: Student Name, Email, Age

In simple terms:
App = Collection of features  
Object = Data storage  
Record = Single data entry  
Field = Specific information

-> Standard vs Custom Objects

Standard Objects:
These are already provided by Salesforce.

Examples:
- Account
- Contact
- Opportunity
- Lead

Custom Objects:
These are created based on business requirements.

Examples:
- Student
- Faculty
- Course
- Department

Why custom objects?
Because every business has unique requirements that standard objects may not support.

-> College Management System Data Model

App Name:
College Management App

Objects:
- Student
- Faculty
- Course
- Department

Relationships:
- One Department can have many Students
- One Department can have many Faculty members
- One Faculty can teach many Courses
- One Student can enroll in many Courses

Lookup Relationships:
- Student → Department
- Faculty → Department
- Course → Faculty

Why relationships matter:
Relationships help connect related data and reduce duplication.

-> Data Model Diagram

Department
   ↓
Students

Department
   ↓
Faculty

Faculty
   ↓
Courses

Students
   ↓
Enrollments

-> Formula Fields

Formula Field 1:
Full Name

Purpose:
Automatically combines First Name + Last Name

Why?
Reduces manual work and prevents mistakes.

Formula Field 2:
Remaining Course Seats

Purpose:
Calculates available seats automatically.

Formula:
Total Seats - Enrolled Students

Why?
Helps admin quickly check course availability.

Formula Field 3:
Student Percentage

Purpose:
Automatically calculates percentage from marks.

Why?
Saves time and avoids manual calculation errors.

-> Validation Rules

Validation Rule 1:
Student email cannot be empty

Why?
Prevents incomplete student records.

Validation Rule 2:
Student age cannot be negative

Why?
Prevents invalid student information.

Validation Rule 3:
Course seats cannot exceed maximum limit

Why?
Prevents overbooking of courses.

-> Why Structured Enterprise Data Matters

Companies cannot manage everything using spreadsheets because:

- Data becomes messy
- Duplicate entries increase
- Relationships cannot be maintained properly
- Hard to scale
- Difficult to generate reports
- Higher chances of errors

Structured data helps businesses:
- Maintain clean records
- Improve decision-making
- Automate workflows
- Scale operations efficiently

-> Why Relationships Are Important

Relationships help connect different objects.

Example:
Without relationships:
Student and course data would be stored separately with repeated information.

With relationships:
Salesforce connects them efficiently without duplication.

-> Formula Fields vs Validation Rules

Formula Fields:
- Used for automatic calculations
- Example: Percentage calculation

Validation Rules:
- Used to block invalid data
- Example: Prevent negative age values

In simple terms:
Formula = Calculate automatically  
Validation = Prevent wrong data entry

-> Reflection

Today I learned:

- How Salesforce stores business data
- Difference between object, field, and record
- Standard vs custom objects
- Why relationships are important
- Formula fields
- Validation rules
- Why structured enterprise systems are better than spreadsheets

-> Trailhead Modules Completed

✅ Data Modeling
<img width="1916" height="1061" alt="Screenshot 2026-05-11 194914" src="https://github.com/user-attachments/assets/eca517ef-725e-421d-b85b-bf84601de2f4" />


Optional:
- Customize a Salesforce Object

-> Screenshots

Add your Trailhead screenshots here:
- Data Modeling completion screenshot
- Formulas and Validation screenshot
