# Ex.No:2(A) CLASS AND OBJECT

## QUESTION:
Create a class Mobile with attributes brand, storage, color. Take input for 2 mobiles and print details.

## AIM:
To write a Java program that reads details of two Mobile objects and prints their brand, storage, and color.

## ALGORITHM :

1.	Start the program.
2.	Import the necessary package 'java.util' and create a Scanner to read user input.
3.	Create the first Mobile object and read its brand, storage, and color from the user.
4.	Create the second Mobile object and read its brand, storage, and color.
5.	Display the details of the first mobile in the required format.
6.	Display the details of the second mobile and close the scanner.
7.	End the program.


## PROGRAM:

```
Developed by: Vikash s
RegisterNumber: 212222240115
```

## SOURCE CODE:

```
import java.util.Scanner;

class Mobile 
{
    String brand;
    int storage;
    String color;
}

public class Main 
{
    public static void main(String[] args) 
    {
        Scanner sc = new Scanner(System.in);

        Mobile m1 = new Mobile();
        m1.brand = sc.next();
        m1.storage = sc.nextInt();
        m1.color = sc.next();

        Mobile m2 = new Mobile();
        m2.brand = sc.next();
        m2.storage = sc.nextInt();
        m2.color = sc.next();

        System.out.println(m1.brand + " | " + m1.storage + "GB | " + m1.color);
        System.out.println(m2.brand + " | " + m2.storage + "GB | " + m2.color);

        sc.close();
    }
}
```


## OUTPUT:

<img width="798" height="267" alt="image" src="https://github.com/user-attachments/assets/35fd2a20-b844-45d2-a275-c6d23fe7dad8" />


## RESULT:
Thus, the program that reads details of two Mobile objects and prints their brand, storage, and color is written and executed successfully.

