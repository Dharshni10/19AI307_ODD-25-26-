# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:
Write a java program to replace each space with a hyphen.

## AIM:
To write a Java program that replaces all spaces in a given string with hyphens (-).

## ALGORITHM :
1.	Start the program and create a Scanner object.
2.	Read a string input from the user.
3.	Use the replace() method to replace all spaces with -.
4.	Display the modified string.
5.	End the program.

## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
Developed by: Dharshni V M
RegisterNumber: 212223240029
*/
```

## SOURCE CODE:
```
import java.util.*;
public class ReplaceSpace{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        String input = sc.nextLine();
        String modified = input.replace(" ","-");
        System.out.println("Modified string: " + modified);
    }
}
```

## OUTPUT:

<img width="812" height="234" alt="image" src="https://github.com/user-attachments/assets/bdabfc05-7f54-4823-8a4b-c6995ddda15c" />

## RESULT:
Thus,the program successfully replaces all spaces in the input string with hyphens.
