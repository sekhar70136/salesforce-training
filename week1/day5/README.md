-> Day 5 - Apex Introduction

-> What is Apex?

Apex is a programming language developed by Salesforce that allows developers to write custom business logic on the Salesforce platform.

It is similar to Java and is used when no-code tools like Flow Builder are not enough.

Apex helps developers:
- Write custom logic
- Automate complex processes
- Perform database operations
- Integrate external systems
- Handle advanced business requirements

Example:
If a student has less than 75% attendance, Apex can automatically block exam registration.

-> Why Salesforce Needs Apex

Salesforce provides many no-code tools like:
- Flow Builder
- Validation Rules
- Formula Fields

But some business problems are too complex for clicks-based tools.

Examples:
- Complex fee calculations
- Payment gateway integration
- Advanced eligibility rules
- Custom notifications
- External API integrations

This is where Apex is needed.

-> Flow vs Apex

Flow:
- No-code automation tool
- Easy to build
- Best for simple workflows
- Faster development

Example:
Send registration confirmation email

Apex:
- Requires coding
- Handles complex logic
- Better for advanced customizations
- More flexible

Example:
Custom scholarship eligibility calculation

In simple terms:
Flow = Simple automation  
Apex = Complex business logic

-> Configuration vs Coding

Configuration:
Uses clicks instead of code.

Examples:
- Creating objects
- Validation rules
- Flow automation
- Formula fields

Coding:
Uses Apex for advanced logic.

Examples:
- External integrations
- Complex calculations
- Custom automation logic

In simple terms:
Configuration = Faster and easier  
Coding = More flexible and powerful

-> Real Examples Where Apex Is Needed

1. Complex Fee Calculation  
Different students may have scholarships, penalties, and discounts.

Why Apex?  
Because the logic becomes too complex for Flow.

2. Payment Gateway Integration  
Students paying fees through external payment apps.

Why Apex?  
External API integration requires code.

3. Advanced Course Eligibility  
Students can register only if they complete prerequisites.

Why Apex?  
Requires advanced conditional logic.

-> Integrated College Management System

CRM:
Student admission and communication management

Objects:
- Student
- Faculty
- Course
- Department
- Fee Payment

Relationships:
- Student → Course
- Faculty → Department
- Course → Faculty

Validation:
- Email cannot be empty
- Age cannot be negative

Formula Fields:
- Remaining seats
- Student percentage

Flow Automation:
- Send registration email
- Fee payment reminders
- Notify faculty when course is full

Apex:
- Scholarship calculation
- Payment integration
- Attendance eligibility logic

-> Pseudocode Examples

Example 1:

IF course seats are full  
THEN block registration

Example 2:

IF attendance < 75%  
THEN notify student

Example 3:

IF fee payment is pending  
THEN send reminder email

-> Why Enterprise Systems Need Programming

Large businesses have complex requirements that cannot always be solved using clicks.

Programming helps:
- Build flexible solutions
- Handle complex logic
- Integrate third-party systems
- Scale applications

Without programming:
Some advanced business needs cannot be fulfilled.

-> Trailhead Modules Completed

✅ Apex & .NET Basics  
<img width="1919" height="1057" alt="salesforce-day5" src="https://github.com/user-attachments/assets/ba48bdf3-95c6-405d-858a-3c68b0aa78e9" />
  

-> End of Day Outcome

By the end of Day 5, I understood:
- What Apex is
- Basic Apex concepts
- Why Salesforce needs programming
- Difference between Flow and Apex
- Difference between configuration and coding
- Real-world Apex use cases
- How enterprise systems combine automation and programming
- How all Salesforce concepts connect together
