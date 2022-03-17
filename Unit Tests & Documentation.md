[Main Readme](https://github.com/shadilios/reading-notes/blob/main/README.md)

# Unit Tests & Documentation

![image](https://martinfowler.com/bliki/images/unitTest/sketch.png)

<br><hr><br>

### What is Unit test?

In basic terms, a Unit test is a function that tests our code for us and makes sure that the output of our functions is equal to a data we pass in manually. (Just like in prep-course where we had a way to test our problems).

There are Unit tests available from Microsoft inside the UnitTesting name space that we can already use without having to write our own.


### Unit test main ideas

* A unit test isn't considered a test if it fails without proper setup on some machines
* that doesn't mean that any test you add to your code isn't helpful, it's just that those tests don't qualify to be called Unit Tests.
* Unit tests test specific parts of your code.

<hr>

### Basic Tutorial to simple Unit test

1. Create a c# console app called (Application) with the following code:

```cs
public class Calculator
{
    public int Add(int x, int y)
    {
        return x + y;
    }
}
```


2. Create a new console app called (Application Tester).
3. In the application Tester and inside the main function, add the following code:

```cs
{
	//instantiate a new object of your Calculator class
	var calculator = new Calculator();
	
	//store the value of the result of that function
    int result = calculator.Add(5, 6);
	
	//if result isn't equal to 11, throw an error
    if (result != 11)
    	throw new InvalidOperationException();
}
```

That's it, that's how you can write the simplest Unit test ever.

<br><hr><br>

### Advanced Tutorial (Using Unit Test Framework)

1. Delete the Application Tester app you created in the Basic Tutorial.
2. Right click on the solution file in the explorer and add a project.
3. Choose Test then Unit Test Project and click Create.

	<b>Note:</b> a good way to name your unit test application is by using this naming convention: (OriginalApplicationName.UnitTest)

4. Inside the created UnitTest1 class, add the following block of code.

```cs
[TestMethod]
    public void TestMethod1()
    {
        var calculator = new Calculator();

        int result = calculator.Add(5, 5);
		
		//compare the value result with the number 10
        Assert.AreEqual(10, result);
    }
```

Now if we run this code, it will show a green check if it passes and also show you how long it took to run in Milli-Seconds.

#### explaination:

 The <b> Assert.AreEqual </b> method is a built in method supplied by Microsoft that can be used like any other functions to make sure our code passes a specific criteria, in this example the method compares the actual result of the function with the value 10.
 
 note: <i>Make sure to read about other built in functions in the UnitTesting namespace</i>
 
 <br><hr><br>
 
 <b>A more detailed source: [Video Tutorial](https://www.youtube.com/watch?v=HYrXogLj7vg)</b>
