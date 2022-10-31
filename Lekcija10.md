
# SQL




## Lekcija 10.

Find the longest time that an employee has been at the studio

```bash
 SELECT MAX(Years_employed) FROM employees;
```

For each role, find the average number of years employed by employees in that role 
```bash
 SELECT Role,AVG(Years_employed) FROM employees GROUP BY Role;
```

Find the total number of employee years worked in each building 

```bash
 SELECT Building,SUM(Years_employed) FROM employees GROUP BY Building;
```




