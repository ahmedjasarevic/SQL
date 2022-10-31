
# SQL




## Lekcija 6.

Find the domestic and international sales for each movie

```bash
ELECT Movies.Id, Movies.Title,Boxoffice.Domestic_sales, Boxoffice.International_sales
FROM Movies INNER JOIN Boxoffice 
ON Movies.Id = Boxoffice.Movie_id
ORDER BY Id ASC;
```
Show the sales numbers for each movie that did better internationally rather than domestically  

```bash
SELECT Movies.Title, Boxoffice.Domestic_sales, Boxoffice.International_sales
FROM Movies 
JOIN Boxoffice 
ON Movies.Id = Boxoffice.Movie_id
WHERE Boxoffice.Domestic_sales < Boxoffice.International_sales;
```

List all the movies by their ratings in descending order 

```bash
SELECT Movies.Title, Boxoffice.Rating
FROM Movies 
JOIN Boxoffice 
ON Movies.Id = Boxoffice.Movie_id
ORDER BY Rating DESC;
```


