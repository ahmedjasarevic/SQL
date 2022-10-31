
# SQL




## Lekcija 7.

Find the list of all buildings that have employees  

```bash
SELECT DISTINCT building FROM employees;
```
Find the list of all buildings and their capacity

```bash
SELECT  Building_name,Capacity FROM Buildings;
```

List all buildings and the distinct employee roles in each building (including empty buildings)

```bash
SELECT DISTINCT building_name, role 
FROM buildings 
  LEFT JOIN employees
    ON building_name = building;
```



