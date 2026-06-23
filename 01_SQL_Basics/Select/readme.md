# SQL Basics

## What Is SQL?

SQL (Structured Query Language) is the language used to communicate with databases.

Think of SQL as a way to ask questions from data.

---

## Why Do We Use It?

We use SQL to:

- Retrieve data
- Filter records
- Analyze information
- Generate reports
- Support business decisions

---

## Basic Syntax

```sql
SELECT *
FROM Patients;
```

---

## Example

```sql
SELECT patient_id,
       patient_name
FROM Patients;
```

### Query Screenshot

<img width="1222" height="820" alt="image" src="https://github.com/user-attachments/assets/23fc92c6-10b5-4081-a267-8ac9036f4912" />
<img width="1287" height="822" alt="image" src="https://github.com/user-attachments/assets/a6bdc526-bebc-4fad-bbb7-89a166e10a25" />


## Interview Question

Q: Difference between SQL and Database?

Answer:

Database stores data.

SQL is the language used to interact with the database.

---

## Common Mistake

Using:

```sql
SELECT patient_name
```

without:

```sql
FROM Patients
```

SQL doesn't know where to fetch the data from.

---

## My Notes

When I started learning SQL, I thought SQL and Database were the same thing.

Now I think of:

Database = Library

SQL = Librarian
