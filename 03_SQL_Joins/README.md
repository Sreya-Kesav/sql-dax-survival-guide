# SQL Joins

## Goal

Learn how tables relate to each other.

---

## Join Types

- [ ] INNER JOIN
- [ ] LEFT JOIN
- [ ] RIGHT JOIN
- [ ] FULL OUTER JOIN
- [ ] CROSS JOIN
- [ ] SELF JOIN

---

## Important Patterns

- [ ] Missing Records
- [ ] Employee-Manager Hierarchy
- [ ] Multi-table Joins
- [ ] Join + Aggregation
- [ ] Join + CASE WHEN

---

## SQL code

```sql
SELECT *
FROM Customers c
LEFT JOIN Orders o
ON c.CustomerID = o.CustomerID
WHERE o.CustomerID IS NULL;
```

## Easy Memory Trick 

INNER JOIN = Common item in both the tables 

LEFT JOIN = Everything on Left

RIGHT JOIN = Everything on Right

FULL JOIN = Everything
