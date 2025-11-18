# Ex.No:2(D) VARIABLE SCOPE AND CONSTRUCTOR

## QUESTION:
Demonstrate variable shadowing by declaring an instance variable and a local variable with the same name inside a method. Print both values.

## AIM:
To write a Java program that demonstrates variable shadowing by declaring an instance variable and a local variable with the same name inside a method and printing both values using this keyword.

## ALGORITHM :
1. Start the program.
2. Import the package java.util.*.
3. Create a class containing an instance variable named n.
4. Inside the class, define a method that accepts a parameter with the same name (n) creating variable shadowing.
5. Inside the method, print the local variable (method parameter) directly.
6. Print the instance variable using this.n to differentiate it from the local variable.
7. In the main method, read a number from the user.
8. Create an object of the class and call the method, passing the local variable.
9. End the program.

## PROGRAM:
 ```
/*
Program to implement a Variable scope and Constructor using Java
Developed by: Dharshni V M
RegisterNumber: 212223240029
*/
```

## SOURCE CODE:
```
import java.util.*;
class Demo{
    int n = 10;
    void show(int n){
        System.out.println("Local variable number: " + n);
        System.out.println("Instance variable number: " + this.n);
    }
}
public class Main{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        Demo demo = new Demo();
        int localNumber = sc.nextInt();
        demo.show(localNumber);
    }
}
```

## OUTPUT:

<img width="714" height="298" alt="image" src="https://github.com/user-attachments/assets/d9e06810-652f-4ce9-839c-dd9dec4e7020" />

## RESULT:
Thus, the Java program demonstrating variable shadowing using an instance variable and a local variable with the same name was successfully written, executed, and verified.
