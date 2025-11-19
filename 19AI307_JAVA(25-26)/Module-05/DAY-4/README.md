# Ex.No:5(D) THREAD PRIORITY

## QUESTION:
Write a java program for determine the priority and name of the current thread.

Note : Read the threadname from the User

## AIM:
To read a thread name from the user and display the current thread’s name and priority.

## ALGORITHM :
1.	Read the thread name from the user.
2.	Get the reference of the current thread using Thread.currentThread().
3.	Set the name of the current thread using setName().
4.	Retrieve the thread’s name and priority using getName() and getPriority().
5.	Display both values.

## PROGRAM:
 ```
/*
Program to implement a Thread Priority Concept using Java
Developed by: Dharshni V M
RegisterNumber: 212223240029
*/
```

## SOURCE CODE:
```
import java.util.Scanner;
public class ThreadInfoExample {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String threadName = scanner.nextLine();
        Thread t = new Thread(() -> {
        }, threadName);
        System.out.println("Priority of Thread: " + t.getPriority());
        System.out.println("Name of Thread: " + t.getName());
        System.out.println(t);
    }
}
```

## OUTPUT:

<img width="694" height="187" alt="image" src="https://github.com/user-attachments/assets/3f06b5a1-6b9b-435a-a678-261b962ab5cf" />

## RESULT:
Thus, the program successfully reads the thread name from the user and displays the current thread’s name and priority.
