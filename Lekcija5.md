
# SQL




## Lekcija 5.

List all the Canadian cities and their populations

```bash
SELECT City,Population FROM north_american_cities WHERE Country = "Canada";
```
Order all the cities in the United States by their latitude from north to south

```bash
SELECT City FROM north_american_cities WHERE Country = "United States" 
ORDER BY LATITUDE DESC;
```

List all the cities west of Chicago, ordered from west to east

```bash
// SELECT City FROM north_american_cities WHERE LONGITUDE < -87.629798
```

List the two largest cities in Mexico (by population)

```bash
SELECT City FROM north_american_cities WHERE Country = "Mexico" ORDER BY POPULATION DESC LIMIT 2;
```

List the third and fourth largest cities (by population) in the United States and their population

```bash
SELECT City,Population FROM north_american_cities WHERE Country = "United States" ORDER BY POPULATION DESC LIMIT 2,2;
```
