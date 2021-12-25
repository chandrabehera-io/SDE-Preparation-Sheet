# String
- Strings, which are widely used in Java programming, are a sequence of characters. In the Java programming language, strings are objects.

> ## Creating Strings
>
-  The most direct way to create a string is to write:
 String greeting = "Hello world!";


> ## String Methods
- Methods used to obtain information about an object are known as accessor methods. One accessor method that you can use with strings is the length() method, which returns the number of characters contained in the string object.

- String method charAt(i), which returns the ith character in the string, counting from 0.

- The String class includes a method, getChars(), to convert a string, or a portion of a string, into an array of characters.
- The String class includes a method for concatenating two strings: string1.concat(string2); 
-  For each object that is not a String, its toString() method is called to convert it to a String.

> ## Creating Format Strings
-  The String class has an equivalent class method, format(), that returns a String object rather than a PrintStream object.
