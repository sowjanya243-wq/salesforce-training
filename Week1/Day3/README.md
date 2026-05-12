#  Week 1 - Day [3]

##  Date: [11-05-2026]


##  Topics Learned
- Objects
- Fields
- Records
- Relationships
- Formula Fields
- Validation Rules
- Schema Builder

---

#  Difference Between App, Object, Record, Field

| Term | Meaning |
|---|---|
| App | Collection of tools, tabs, and objects |
| Object | Database table |
| Record | Single row of data |
| Field | Column inside object |

---

#  Standard vs Custom Objects

## Standard Objects
Objects already provided by Salesforce.

Examples:
- Account
- Contact
- Opportunity

## Custom Objects
Objects created by users based on business needs.

Examples:
- Property
- Offer
- Student

---

# College Management Data Model

## Objects
- Student
- Faculty
- Course
- Department

## Relationships
- Department → Student
- Department → Faculty
- Faculty → Course

Relationship Type:
- Lookup Relationships

---

#  Formula Fields

| Formula Field | Purpose |
|---|---|
| Full Name | Combine first and last name |
| Percentage | Automatically calculate marks percentage |
| Remaining Seats | Calculate available course seats |

## Why Formula Fields?
Formula fields automatically calculate values and reduce manual work and errors.

---

#  Validation Rules

| Validation Rule | Prevents |
|---|---|
| Age cannot be negative | Invalid student data |
| Email cannot be empty | Missing contact information |
| Seats cannot exceed limit | Incorrect course data |

## Why Validation Rules?
Validation rules stop invalid or incorrect data from being saved.

---

#  Schema Builder

Schema Builder helps visualize objects, fields, and relationships in Salesforce.

---

#  Reflection

Companies need structured data because it keeps information organized, connected, accurate, and easy to manage. Random spreadsheets can cause duplicate data, errors, and confusion.

---

#  Screenshots


- Data Modeling module completed
- Formula Fields challenge passed
- Validation Rule challenge passed
- Schema Builder challenge passed
