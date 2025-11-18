# Ex.No:1(D) ARRAYS

## QUESTION:
Write a Java program to print all elements in an array that are greater than a given value

## AIM:
To write a Java program that prints all elements in an array greater than a given value.

## ALGORITHM :
1. Start the program and create a Scanner object.
2. Read the size n and elements of the array.
3. Read a value to compare with.
4. Use a loop to check and print elements greater than the given value.
5. End the program.

## PROGRAM:
 ```
/*
Program to implement a Array concept using Java
Developed by: Dharshni V M
RegisterNumber: 212223240029
*/
```

## SOURCE CODE:
```
import java.util.Scanner;
public class ElementsGreaterThanX {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int n = scanner.nextInt();    
        int[] arr = new int[n];
        for(int i = 0; i < n; i++) {
            arr[i] = scanner.nextInt(); 
        }
        int x = scanner.nextInt();     
        boolean found = false;
        for(int i = 0; i < n; i++) {
            if(arr[i] > x) {
                System.out.println(arr[i]);
                found = true;
            }
        }
        if(!found) {
            System.out.println("No elements greater than " + x);
        }
    }
}

```

## OUTPUT:

<img width="679" height="585" alt="image" src="https://github.com/user-attachments/assets/48a9463e-8e2a-43e6-99f9-7d7b37661d89" />

## RESULT:
Thus,the program successfully prints all array elements greater than the given value.
