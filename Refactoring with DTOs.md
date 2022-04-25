[Main Readme](https://github.com/shadilios/reading-notes/blob/main/README.md)

# Refactoring with DTOs

![img](https://cdn.ttgtmedia.com/rms/onlineimages/code_refactoring_process-f_mobile.png)


<br><hr><br>
## Why use DTOs

* our data is exposed to the client, so we need a way to hide it, because sometimes we want to hide sensitive properties from the client and make them inaccessible.
* A DTO is a great choice when you pass a lightweight object.


<br><hr><br>
## Uses of DTOs

1. Use DTOs for abstraction:
    
2. Use DTOs for data hiding:
    


<br><hr><br>
## DTO class tutorial

Let's say you want to create a DTO class for the following class, to hide sensitive information.

```
class Student
    {
        public int Id { get; set; }
        public string Name { get; set; }
        public string Address { get; set; }
        public double GPA { get; set; }
    }

```
You can create a new class with nameDTO naming convention & take the non sensitive information you want.
```
class StudentDTO
    {
        public int Id { get; set; }
        public string Name { get; set; }

    }
```
<br><hr><br>

