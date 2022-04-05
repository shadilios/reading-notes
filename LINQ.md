[Main Readme](https://github.com/shadilios/reading-notes/blob/main/README.md)  

# LINQ

![image](https://static.javatpoint.com/tutorial/linq/images/linq-2.png)


<br><hr><br>

### What is LINQ?

Short for Language Integrated Query, which is a way to obtain data, filter it and use specific parts of it.  

<br><hr><br>

### How to use LINQ?

Just like SQL, we can select specific data based on conditions we provide.  
Exmaple: Look through the cars, and find me each car that it's model property is equal to "Mercedes".  

```
var carQuery = from car in cars
               where car.model == "Mercedes"
               select car;
```

<br><hr><br>

### Query functionality

Query share the same functionality we studied in SQL, and examples of these Functionalities are:  

1. Filtering
2. Ordering
3. Grouping
4. Joining

