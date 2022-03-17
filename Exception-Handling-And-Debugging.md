[Main Readme](https://github.com/shadilios/reading-notes/blob/main/README.md)

# Exception Handling & Debugging

![Image](https://static.javatpoint.com/blog/images/debugging2.png)

### 1. What is Debugging?

Debugging is running your code line by line to determine the line that crashes your program.  
An Advanced way of doing this while avoiding program crashing is exception handling, where we alert our code where it might fail, and tell it to basically notify us while ignoring it.  

<br><hr><br>
### 2. Try & Catch

Try & Catch are keywords used in C# where we use the Try keyword to tell the code to "Try" and run this code, and we use the Catch keyword to tell it to "Catch" any errors that might occur without breaking my program.  

An example of doing this block of code:

```
try
{
	var a = Console.ReadLine();
	double z = a + 3;
}
catch(Exception.e)
{
	Console.WriteLine(e.Message);
}

```

An error will occur because the ReadLine command returns a string, and if we try to do any mathmetical operation with a string will do an error.

<br><hr><br>
### 3. Real World Scenario

In the Therac-25 which was a medical radiation therapy machine controlled by a computer program, the company reused an old software and assumed it was 100% safe without doing any debugging, but then errors started ocurring where patients took extra doses of radiation resulting in death or injuries.  

Due to this, The international standard IEC 62304 was created, which is a standard that specifies life cycle requirements for developing machines that are considered "Medical".





