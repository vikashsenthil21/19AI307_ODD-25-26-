# Ex.No:2(B) METHODS

## QUESTION:
Write a method int cube(int x) that calls a method int square(int x) internally to calculate the cube as x * square(x).

## AIM:
To write a Java program that computes the cube of a number using a cube method that internally calls a square method.

## ALGORITHM :

1.	Start the program.
2.	Import the necessary package 'java.util' and create a Scanner to read user input.
3.	Pass this number to the cube(x) method.
4.	Inside cube(x), call the square(x) method to compute x^2.
5.	Multiply x by the returned square value to compute the cube.
6.	Return the cube value to main().
7.	Print the final cube result.
8.	End the program.


## PROGRAM:

```
Program to implement a Methods using Java
Developed by: Sathyaa R
RegisterNumber: 212223100052
```

## SOURCE CODE:

```
import java.util.Scanner;

public class Main 
{
    public static void main(String[] args) 
    {
        Scanner sc = new Scanner(System.in);
        int num = sc.nextInt();
        System.out.println(cube(num));
    }

    static int square(int x) 
    {
        return x * x;
    }
    static int cube(int x) 
    {
        return x * square(x);
    }
}
```

## OUTPUT:

<img width="347" height="170" alt="image" src="https://github.com/user-attachments/assets/1d06f09b-b967-4bb6-b0fb-dcf8057b8915" />


## RESULT:
Thus, the program that computes the cube of a number using a cube method that internally calls a square method is written and executed successfully.

