
# SQL




## Lekcija 13.

Add the studio's new production, Toy Story 4 to the list of movies (you can use any director) 

```bash
INSERT INTO movies (Id,Title,Director)
VALUES(15,"Toy Story 4","Dan Schanlon");
```

Toy Story 4 has been released to critical acclaim! It had a rating of 8.7, and made 340 million domestically and 270 million internationally. Add the record to the BoxOffice table.
```bash
INSERT INTO Boxoffice (Movie_id,Rating,Domestic_sales,International_sales)
VALUES(15,8.7,3400000,2700000);
```





