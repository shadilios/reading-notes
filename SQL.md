[Main Readme](https://github.com/shadilios/reading-notes/blob/main/README.md)

# Summary:
sql is used to manage data in tables, whether store it in the database or retrie it and use it with our code.  

<hr>

# My answers:

The following will have my tasks answered, with the code I worte on each task.

<hr>

##### Lesson 1
![1](https://user-images.githubusercontent.com/70282602/158023925-ce0c741e-cb89-408b-8cb4-59854d488dde.png)

SELECT title FROM movies;  
SELECT director FROM movies;   
SELECT title, director FROM movies;  
SELECT title, year FROM movies;  
SELECT * FROM movies;  

<hr>

##### Lesson 2
![2](https://user-images.githubusercontent.com/70282602/158023927-e6248e36-e453-4b98-b51f-f9746a0dd304.png)

SELECT * FROM Movies where ID = 6;  
SELECT * FROM Movies where Year BETWEEN 2000 AND 2010;  
SELECT * FROM Movies where Year NOT BETWEEN 2000 AND 2010;  
SELECT title, year FROM movies WHERE year <= 2003;  



<hr>

##### Lesson 3
![3](https://user-images.githubusercontent.com/70282602/158023932-939e965d-0d80-49f7-94e6-152026fadb96.png)

SELECT title, director FROM movies WHERE title LIKE "Toy Story%";  
SELECT * FROM movies where director LIKE "John Lasseter%";  
SELECT * FROM movies where director NOT LIKE "John Lasseter%";  
SELECT * FROM movies where title LIKE "Wall-%"  

<hr>

##### Lesson 4
![2022-03-12 16_05_28-SQLBolt - Learn SQL - SQL Lesson 4_ Filtering and sorting Query results - Opera](https://user-images.githubusercontent.com/70282602/158023938-a46b928e-c4ed-4afb-90ae-13953fc6b791.png)

SELECT DISTINCT director FROM movies ORDER BY director ASC;  
SELECT * FROM movies ORDER BY year DESC LIMIT 4;  
SELECT * FROM movies ORDER BY Title ASC LIMIT 5;  
SELECT Title FROM movies ORDER BY Title ASC LIMIT 5 OFFSET 5;  

<hr>

##### Lesson 5
![4](https://user-images.githubusercontent.com/70282602/158023940-4bbbb1b6-0122-4f77-b1ca-730fefaaaf89.png)

SELECT * FROM north_american_cities WHERE Country Like "Canada" ;  
SELECT * FROM north_american_cities WHERE Country Like "United States" ORDER BY Latitude DESC;  

SELECT city, longitude FROM north_american_cities
WHERE longitude < -87.629798
ORDER BY longitude ASC;  

SELECT city, population FROM north_american_cities
WHERE country LIKE "United States"
ORDER BY population DESC
LIMIT 2 OFFSET 2;  


<hr>

##### Lesson 6
![5](https://user-images.githubusercontent.com/70282602/158023945-78f053f9-5f29-4992-9695-2f15b7aa2478.png)

lesson 6
SELECT title, domestic_sales, international_sales 
FROM movies
  JOIN boxoffice
    ON movies.id = boxoffice.movie_id;  

SELECT title, domestic_sales, international_sales
FROM movies
  JOIN boxoffice
    ON movies.id = boxoffice.movie_id
WHERE international_sales > domestic_sales;  

SELECT title, rating
FROM movies
  JOIN boxoffice
    ON movies.id = boxoffice.movie_id
ORDER BY rating DESC;  


<hr>

