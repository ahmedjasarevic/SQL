
# SQL



## Lekcija 17.

Add a column named Aspect_ratio with a FLOAT data type to store the aspect-ratio each movie was released in.  

```bash
ALTER TABLE Movies
ADD Aspect_ratio FLOAT; 
```

Add another column named Language with a TEXT data type to store the language that the movie was released in. Ensure that the default for this language is English
```bash
ALTER TABLE Movies
ADD Language TEXT
DEFAULT ENGLISH;
```





