# Ex.No:1(D) ARRAYS

## QUESTION:
Write a Java program to reverse an array

## AIM:
To write a Java program that reads an array from the user and prints its elements in reverse order.

## ALGORITHM :
1.Start the program.

2.Create a Scanner object to read input.

3.Read the size of the array n.

4.Declare an array of size n.

5.Read all n elements from the user and store them in the array.

6.Loop from the last index to the first index and print each element.

7.End the program.




## PROGRAM:
 ```
/*
Developed by: Vikash s
RegisterNumber: 212222240115 
*/
```

## SOURCE CODE:

```
import java.util.Scanner;

public class ReverseArray {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int[] arr = new int[n];
        for (int i = 0; i < n; i++) {
            arr[i] = sc.nextInt();
        }

        for (int i = n - 1; i >= 0; i--) {
            System.out.print(arr[i] + " ");
        }

        sc.close();
    }
}
```




## OUTPUT:

<img width="501" height="562" alt="image" src="https://github.com/user-attachments/assets/f2c212be-7e2c-45de-a284-0672ba3c2890" />


## RESULT:
The program successfully reads the array elements and displays them in reverse order.
