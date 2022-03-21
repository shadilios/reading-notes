# Classes & Objects

![Image](https://miro.medium.com/max/1400/1*xioo_jcb22JuG7Xqndau8w.png)




### Phrases
1. Class: a class is a unit that holds all of our variables & functions, it can also be the mold that we use to create our objects from.
2. Object: an object is a data type or instance of a class that holds multiple variables & functions that are written inside the class.
3. Constructor: A constructor is a special kind of function that gets called whenever we create (instantiate) an object from the class, the constructor also holds the same name as the class name.

<br><hr><br>

### How to create a Class?

The following script is of a class called Animal:

```
public class Animal
    {
        string animalName;
        int age;
        double weight;
    }
```  

Notice how it hold variables that don't have values, that's because we're declaring a Mold and telling our Program that we have this data type that will have the animalName, age & weight properties.  
So each time we create an object from this class or Mold, each of those objects will hold those properties & we will have the option to assign values to them.

<br><hr><br>
### How to create a constructor?

The following script is of the same class we created before, but we added a constructor to it.

```
public class Animal
    {
        string animalName;
        int age;
        double weight;

        public Animal(string name, int age, double weight)
        {
			this.animalName = name;
			this.age = age;
			this.weight = weight;
        }
    }
```
What happens when we create an object, is that it assigns the properties to that specific created object using the "this" keyword, which points at the object not the class.

<br><hr><br>
### How to create an object from a class?

In our main function  (or any  other function we want to create our object within):
```
Animal myAnimal = new Animal("Rex", 6, 9.3);
```
First thing to notice is the line itself, it looks a little bit as if we declared some data type like an array, or any other data type that uses the new keyword.  
What we did here, was basically create an animal that holds the name "Rex", age 6 years old & weight of 9.3 kg.  
* NOTE: There's another way of creating objects without using constructors, but it's a dull & long process and I believe this should be the standard.

