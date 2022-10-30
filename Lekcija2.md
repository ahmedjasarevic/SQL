
# SQL




## Lekcija 2.

Find the movie with a row id of 6 

```bash
SELECT Title FROM movies WHERE ID = 6;
```
Find the movies released in the years between 2000 and 2010 

```bash
SELECT Title FROM movies WHERE Year >= 2000 AND Year <= 2010
```

Find the movies not released in the years between 2000 and 2010

```bash
SELECT Title FROM movies WHERE Year NOT BETWEEN  2000 AND 2010
```

Find the first 5 Pixar movies and their release year

```bash
SELECT Title FROM movies WHERE ID >= 1 AND ID <= 5
```


