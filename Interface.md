[Main Readme](https://github.com/shadilios/reading-notes/blob/main/README.md)

# Interface

![Image](https://d8it4huxumps7.cloudfront.net/bites/wp-content/banners/2022/2/620e4a30635f1_difference_between_abstract_class_and_interface_in_c.png)

<br><hr><br>

### What is an Interface?
It's something like a class, but completley different.
A building look that's used like a mold to shape our classes, but never contain Function details or variables.
Only declerations are allowed.


<br><hr><br>

### Syntax & Naming convention:

Creating an interface is just like creating a class, but instead of using the class keyword, we use the keyword Interface.  
Also the name of the interface we create usually starts with a Capital I letter.

* Exmaple:

```
public interface ITaxCalculator()
{
	int Calculate();
}
```


### Why do we use it?

Interfaces are used to add the building blocks to some functionality that might not exists currently, but added in the future.  
It basically gives us an option to improve without having to write everything from scratch, a mere decleration that holds the mold for our building blocks.  


<br><hr><br>

