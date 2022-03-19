[Main Readme](https://github.com/shadilios/reading-notes/blob/main/README.md)

# System I.O

### What is System I.O?
It's a collection of namespaces that enable the user to read and write to data & files.

It also perform compressions and decompression processes.

<br><hr><br>

### Functinality:
System I.O has many functionalities that are listed below but not limited to:

- Files & Directories.  
- Streams (Reading, Writing & seeking).  
- Compression & Decompression.  

<br><hr><br>

### How to Write to a file?

There are many classes used for this purpose, in the following lines we will be explaining the [StreamWriter Class](https://docs.microsoft.com/en-us/dotnet/api/system.io.streamwriter?view=net-6.0) way in writing few lines into a file.

1. Make sure to add the following line at the top of your program:

```
using System.IO;
```

2. Declare a string varialbe that you will be writing to a specific file:

```
string myLine = "Hello world in a text file!";
```

3. Declare a string variable and store the path you will be writing in.

```
string myPath = Enviroment.GetFolderPath(Enviroment.MyFolder.MyDocuments);
```

4. Finally, add the following line that creates your file and executes your Line into the file.

```
using (StreamWriter outputFile = new StreamWriter(Path.Combine(myPath, "myFileName.txt")))
{
	outputFile.WriteLine(myLine);
}
```

5. Your script at the end should look something like this:

```
using System;
using System.IO;

class Program
{
    static void Main(string[] args)
    {

        // Create a string with the lines of text
        string myLine = "Hello world in a text file!";

        // Set a variable to the Documents path.
        string myPath = Enviroment.GetFolderPath(Enviroment.MyFolder.MyDocuments);

        // Write the string to a new file named "myFileName.txt".
	        using (StreamWriter outputFile = new StreamWriter(Path.Combine(myPath, "myFileName.txt")))
		{
			outputFile.WriteLine(myLine);
		}
    }
}
```
