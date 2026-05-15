# App vs Object vs Record vs Field

## App
An app is a collection of tabs, objects, and features designed for a business purpose.

## Object
An object is a database table that stores data.

## Record
A record is a single row of data inside an object.

## Field
A field stores a specific piece of information in a record.
# Standard vs Custom Objects

## Standard Objects
Objects already provided by Salesforce such as Account, Contact, Opportunity.

## Custom Objects
Objects created by users according to business needs such as Student, Course, Faculty.
# College Data Model

## Objects
- Student
- Faculty
- Course
- Department

## Relationships
- One Department has many Courses
- One Faculty teaches many Courses
- One Course has many Students

## Relationship Types
- Department → Course : Lookup
- Faculty → Course : Lookup
- Course → Student : Lookup
- # Formula Fields

## Percentage
Automatically calculates student percentage from marks.

## Remaining Seats
Calculates available seats in a course.

## Full Name
Combines first name and last name automatically.
# Validation Rules

## Email Cannot Be Empty
Prevents saving incomplete student records.

## Age Cannot Be Negative
Prevents invalid age values.

## Seats Cannot Exceed Limit
Prevents overbooking of courses.
# Reflection

Structured enterprise data helps companies organize, search, secure, and maintain large amounts of business information efficiently. Random spreadsheets can cause duplicate data, inconsistency, and errors.
