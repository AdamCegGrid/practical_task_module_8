# SQL task:

1. Download DB and pdf schema
2. Prepare query for:
    - Select all publishers (publishers) that are from USA
    - Select all publishers (publishers) that are NOT from USA sort by name

<sub>*Attach requests for queries and screenshots with results*</sub>

### Select all publishers (publishers) that are from USA

```sql
SELECT *
FROM publishers
WHERE country = 'USA';
```

![Solution_1](Solution_1.png)

### Select all publishers (publishers) that are NOT from USA sort by name

```sql
SELECT *
FROM publishers
WHERE country <> 'USA'
ORDER BY pub_name ASC;
```

![Solution_2](Solution_2.png)