
# SQL




## Lekcija 11.


Find the number of Artists in the studio (without a HAVING clause) 

```bash
 SELECT COUNT(ROLE) FROM employees WHERE ROLE LIKE "ARTIST";
```
Find the number of Employees of each role in the studio 

```bash
SELECT Role,COUNT(ROLE) FROM employees GROUP BY ROLE;
```

Find the total number of years employed by all Engineers 

```bash
 SELECT Role,SUM(Years_employed) FROM employees GROUP BY ROLE HAVING ROLE LIKE "ENGINEER";
```




