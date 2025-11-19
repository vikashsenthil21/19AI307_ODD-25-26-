# Ex.No:2(B) METHODS

## QUESTION:
Write a method named displayMessage() that prints "Welcome to Java Methods!". Call this method from the main() method.

## AIM:
To write a Java program that defines a method displayMessage() to print a welcome message and call this method from the main() method.

## ALGORITHM :
1.Start the program.
2.Create a class containing the method displayMessage() that prints "Welcome to Java Methods!".
3.In the main() method, create an object of the class.
4.Call the displayMessage() method using the object.
5.End the program.




## PROGRAM:
 ```
Developed by: Vikash s
RegisterNumber:  212222240115

```

## SOURCE CODE:
```
public class Message {

    public void displayMessage() {
        System.out.println("Welcome to Java Methods!");
    }

    public static void main(String[] args) {
        Message obj = new Message();
        obj.displayMessage();
    }
}
```





## OUTPUT:

<img width="695" height="129" alt="image" src="https://github.com/user-attachments/assets/da3b0e2c-53b6-4afb-8fe6-e5d276d1c80d" />


## RESULT:
The program successfully prints "Welcome to Java Methods!" by calling the user-defined method.
