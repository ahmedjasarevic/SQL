
# SQL





## Lekcija 12.

Find the number of movies each director has directed 

```bash
SELECT Director,COUNT(Director) FROM movies GROUP BY DIRECTOR;
```

Find the total domestic and international sales that can be attributed to each director
```bash
SELECT Director,SUM(Domestic_sales+International_sales) AS total FROM movies JOIN Boxoffice ON Movies.Id = Boxoffice.Movie_id GROUP BY DIRECTOR;
```




