# Database Constraints

## What are Constraints?

Constraints are rules applied to table columns to maintain data integrity and accuracy.

---

## Types of Constraints

### 1. PRIMARY KEY
- Uniquely identifies each row.
- Cannot contain NULL values.

Example:

```sql
CREATE TABLE Student (
    id INT PRIMARY KEY,
    name VARCHAR(50)
);
```

---

### 2. FOREIGN KEY

Maintains relationships between tables.

```sql
CREATE TABLE Orders (
    order_id INT PRIMARY KEY,
    customer_id INT,
    FOREIGN KEY(customer_id)
    REFERENCES Customers(customer_id)
);
```

---

### 3. UNIQUE

Prevents duplicate values.

```sql
email VARCHAR(100) UNIQUE
```

---

### 4. NOT NULL

Does not allow NULL values.

```sql
name VARCHAR(50) NOT NULL
```

---

### 5. CHECK

Restricts acceptable values.

```sql
age INT CHECK(age >= 18)
```

---

### 6. DEFAULT

Provides a default value.

```sql
status VARCHAR(20) DEFAULT 'Pending'
```

---

## Advantages

- Improves data quality
- Prevents invalid data
- Maintains consistency
