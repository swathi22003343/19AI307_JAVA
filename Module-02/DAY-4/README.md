# Ex.No:2(D) MULTI-DIMENSIONAL ARRAY

## AIM:
To create a java program that returns the sum of all the values in a 2D array.

## ALGORITHM :
1.	Start the program.
2.	Import `Scanner` and define class `sum`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read `rows` and `cols` from user
-	c) Declare 2D array `arr[rows][cols]`
4.	Populate `arr` using nested loops with user input
5.	Initialize `sum` to `0`
6.	Calculate the sum of all elements in `arr` using nested loops
7.	Print "The sum of all values in the 2D array is: " + `sum`
8.	End



## PROGRAM:
 ```
/*
Program to implement a Multi Dimensional Array using Java
Developed by:SWATHI D 
RegisterNumber:212222230154 
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

      
        int rows = scanner.nextInt();

        int cols = scanner.nextInt();

        int[][] array = new int[rows][cols];
        int sum = 0;

 
        for (int i = 0; i < rows; i++) {
            for (int j = 0; j < cols; j++) {
                array[i][j] = scanner.nextInt();
                sum += array[i][j];
            }
        }

        
        System.out.println("The sum of all values in the 2D array is: " + sum);

        scanner.close();
    }
}
```







## OUTPUT:
![image](https://github.com/user-attachments/assets/a9a7a263-0e57-4364-a63d-f14bf2c005a7)



## RESULT:
Thus the java program that returns the sum of all the values in a 2D array was executed successfully.


