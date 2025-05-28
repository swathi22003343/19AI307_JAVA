# Ex.No:9(E) STRING WRITER

## AIM:
To write a Java program that prints the string "This is the text in the string." using the StringWriter class.
## ALGORITHM :

a.	Start the program.

b.	Import java.io.StringWriter.

c.	Define the string: "This is the text in the string.".

d.	Create a StringWriter object.

e.	Write the string into the StringWriter object using .write()

f.	Print the contents of the StringWriter using .toString() or directly

g.	Close the StringWriter.

h.	End the program.

## PROGRAM:
 ```
/*
Program to implement a STRING WRITER
Developed by: SWATHI D
RegisterNumber: 212222230154
*/
```

## Sourcecode.java:

```python
import java.io.StringWriter;
public class Main {
  public static void main(String[] args) {
    String data = "This is the text in the string.";
    try {
      StringWriter s=new StringWriter();
      s.write(data);
      System.out.println("Data in the StringWriter: "+s);
      s.close();   
    }
    catch(Exception e) {
      e.getStackTrace();
    }
  }
}
```



## OUTPUT:

![image](https://github.com/user-attachments/assets/e1eb8a85-df8b-45e8-bee4-8e67c347e8a6)


## RESULT:
Thus, the Java program was successfully implemented to print a string using the StringWriter class and displayed the result on the output screen.
