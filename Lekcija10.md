
# SQL




## Lekcija 4.

List all directors of Pixar movies (alphabetically), without duplicates 

```bash
 SELECT DISTINCT Director FROM movies ORDER BY Director ASC;
```

List the last four Pixar movies released (ordered from most recent to least) 
```bash
SELECT  Title FROM movies ORDER BY Year DESC LIMIT 4;
```

List the first five Pixar movies sorted alphabetically

```bash
SELECT  Title FROM movies ORDER BY Title ASC LIMIT 5;
```

List the next five Pixar movies sorted alphabetically

```bash
SELECT  Title FROM movies ORDER BY Title ASC LIMIT 5,5;
```


