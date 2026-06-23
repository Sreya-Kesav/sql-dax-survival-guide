# SQL SELECT

## What Is It?

SELECT is the most fundamental SQL statement used to retrieve data from a database table.

---

## Why Do We Use It?

Whenever we want to view, analyze, or report on data, we use SELECT.

Examples:

- View patient records
- Calculate revenue
- Analyze appointments
- Generate reports
  
## Basic Syntax

```sql
SELECT *
FROM Patients;
```
### Query Screenshot
<img width="330" height="205" alt="image" src="https://github.com/user-attachments/assets/9b0b2b66-161d-4793-baae-bd567c87a423" />



### Result Screenshot
<img width="1187" height="702" alt="image" src="https://github.com/user-attachments/assets/b514e865-bc18-4dcf-8e9e-2c9630be24d6" />



## Example

```sql
SELECT patient_id,
       patient_name
FROM Patients;
```

### Query Screenshot
<img width="352" height="251" alt="image" src="https://github.com/user-attachments/assets/db2e141b-7e9f-4763-95e4-461403de74ec" />


### Result screenshot
<img width="406" height="512" alt="image" src="https://github.com/user-attachments/assets/07f9a189-6614-42eb-8355-dfc298cdb86b" />



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


## My Notes

1. When I started learning SQL, I thought SQL and Database were the same thing.

Now I think of:

Database = Library

SQL = Librarian

2. Asterix next to "select" brings in every column which is generally not an optimal solution
   and makes the code run slower when there are thousands of rows. Hence, it's important to mention the names of the column

