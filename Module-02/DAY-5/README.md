# Ex.No:2(E)  SECOND LARGEST NUMBER IN AN ARRAY

## AIM:

Create a java program to find second largest number in an array.


## ALGORITHM :
STEP1:Start the program.

STEP2:Read the size of the array from the user.

STEP3:Declare an array of the given size.

STEP4:Read the array elements from the user.

STEP6:Initialize two variables fmax and smax with the first element of the array.

STEP7:Traverse the array using a loop:

STEP8:After the loop ends, print the second largest number smax.

STEP9:End the program.


	

## PROGRAM:
 ```
/*
Program to implement a Smallest Element in an Array
Developed by:SWATHI D 
RegisterNumber:212222230154  
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

public class ArrayProgram {

  
  public static int secondLargest(int[] arr) {
    
    
    int fmax = 0; 
    int smax = 0; 

    
    fmax = arr[0];
    smax = arr[0];

    for (int i = 1; i < arr.length; i++) {
      if (fmax < arr[i]) {
        smax = fmax;
        fmax = arr[i];
      } else if(smax < arr[i]) {
        smax = arr[i];
      }
    }

    return smax;
  }
  
  public static void main(String[] args) {
    
    Scanner scan = new Scanner(System.in);

   
    int length = 0;
    int numbers[] = null;

   
   
    length = scan.nextInt();


    numbers = new int[length];


    for (int i = 0; i < numbers.length; i++) {
      numbers[i] = scan.nextInt();
    }

    System.out.println("Second largest element = " 
                         + secondLargest(numbers));

    
    scan.close();
  }
}
```







## OUTPUT:
![image](https://github.com/user-attachments/assets/db0ee543-ba22-4f2e-9aa8-77a3c6151b22)



## RESULT:
Thus, the Java program successfully reads the array size and elements from the user and correctly finds and prints the second largest number in the array.


