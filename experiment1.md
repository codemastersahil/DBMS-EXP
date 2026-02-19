
------------------------------------------------------------------------

## Aim

To perform table creation, deletion, updating and alteration operations
using MariaDB.

------------------------------------------------------------------------

## Software Used

-   MariaDB / MySQL
-   Visual Studio Code

------------------------------------------------------------------------

## Queries

### 1. Create Employee_master table with data using Employee table

``` sql
CREATE TABLE Employee_master AS
SELECT * FROM EMPLOYEE;
```

------------------------------------------------------------------------

### 2. Delete all records from Employee_master whose DeptNo is 10

``` sql
DELETE FROM Employee_master
WHERE DEPTNO = 10;
```

------------------------------------------------------------------------

### 3. Increase salary by 10% for employees of DeptNo 20

``` sql
UPDATE Employee_master
SET SAL = SAL * 1.10
WHERE DEPTNO = 20;
```

------------------------------------------------------------------------

### 4. Alter SAL column datatype to DECIMAL(10,2)

``` sql
ALTER TABLE Employee_master
MODIFY SAL DECIMAL(10,2);
```

------------------------------------------------------------------------

### 5. Drop Employee_master table

``` sql
DROP TABLE Employee_master;
```

------------------------------------------------------------------------

## Result

The required SQL operations such as table creation, deletion, updating,
alteration, and dropping were successfully executed using MariaDB.
