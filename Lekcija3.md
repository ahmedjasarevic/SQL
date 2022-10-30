
# SQL




## Lekcija 3.

Find all the Toy Story movies

```bash
SELECT Title FROM movies WHERE Title LIKE "Toy%";
```
Find all the movies directed by John Lasseter 

```bash
SELECT Title FROM movies WHERE Director LIKE "John%";
```

Find all the movies (and director) not directed by John Lasseter 

```bash
SELECT Title FROM movies WHERE Director NOT LIKE "John%";
```

Find all the WALL-* movies

```bash
SELECT Title FROM movies WHERE Title  LIKE "Wall%";

```


