
# SQL




## Lekcija 8.

find the name and role of all employees who have not been assigned to a building

```bash
SELECT Role,Name FROM employees WHERE Building IS NULL;
```
Find the names of the buildings that hold no employees 

```bash
SELECT Building_name FROM Buildings LEFT JOIN Employees ON BuildinG_name = Building WHERE Building IS NULL;
```




