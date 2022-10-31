
# SQL




## Lekcija 9.

List all movies and their combined sales in millions of dollars

```bash
SELECT title, (domestic_sales + international_sales) / 1000000 AS millions
FROM movies
  JOIN boxoffice
    ON movies.id = boxoffice.movie_id;
```

List all movies and their ratings in percent
```bash
SELECT title, rating * 10 AS Percent
FROM movies
  JOIN boxoffice
    ON movies.id = boxoffice.movie_id;
```

List all movies that were released on even number years

```bash
SELECT title
FROM movies
  JOIN boxoffice
    ON movies.id = boxoffice.movie_id
    WHERE Year % 2 == 0;
```




