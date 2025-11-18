# Ex.No:2(A) CLASS AND OBJECT

## QUESTION:
Define a class Teacher with attributes: name (String), subject (String), and experience (int, years). 

## AIM:
To define a Java class Teacher with attributes name, subject, and experience.

## ALGORITHM :
1.	Create a class named Teacher.
2.	Declare attributes name, subject, and experience.
3.	Define a constructor to initialize these attributes.
4.	Add a method displayDetails() to print teacher details.
5.	End the program.

## PROGRAM:
 ```
/*
Program to implement a Class and Objects using Java
Developed by: Dharshni V M
RegisterNumber: 212223240029
*/
```

## SOURCE CODE:
```
import java.util.Scanner;
class Teacher {
    String name;
    String subject;
    int experience;
    void printMessage() {
        System.out.print("Mr. " + name + " teaches " + subject + " and has " + experience + " years experience.");
    }
}
class prog {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        Teacher t = new Teacher();
        t.name = sc.nextLine();
        t.subject = sc.nextLine();
        t.experience = sc.nextInt();
        t.printMessage();
    }
}
```

## OUTPUT:

<img width="1184" height="341" alt="image" src="https://github.com/user-attachments/assets/eab401b8-6d38-4b5f-a642-b3144b95320a" />

## RESULT:
Thus, the Teacher class is successfully defined with the required attributes and methods.
