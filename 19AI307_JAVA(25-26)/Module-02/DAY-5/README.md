# Ex.No:2(E) ACCESS MODIFIERS

## QUESTION:
Create a class SpeedLimit with a final method displayLimit() that prints "Max Speed: 80 km/h". Try to override it in a subclass. Show that overriding a final method is not allowed.

## AIM:
To write a Java program showing that a final method in a superclass cannot be overridden in a subclass.

## ALGORITHM :

1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Define a class SpeedLimit with a final method displayLimit().
4.	Create a subclass HighwaySpeed that extends SpeedLimit.
5.	Attempt to override the displayLimit() method in the subclass (this will cause a compile-time error, proving final methods cannot be overridden).
6.	In the main class, create an object of HighwaySpeed.
7.	Call displayLimit() using the subclass object (the parent method executes).
8.	End the program.


## PROGRAM:

```
Developed by: Vikash s
RegisterNumber: 212222240115
```

## SOURCE CODE:

```
class SpeedLimit 
{
    final void displayLimit() 
    {
        System.out.println("Max Speed: 80 km/h");
    }
}

class HighwaySpeed extends SpeedLimit 
{
}

class prog
{
    public static void main(String[] argv)
    {
        HighwaySpeed obj = new HighwaySpeed();
        obj.displayLimit();
    }
}
```


## OUTPUT:

<img width="509" height="172" alt="image" src="https://github.com/user-attachments/assets/8513f8bd-3782-456b-be78-98b7584f1e03" />


## RESULT:
Thus, the program showing that a final method in a superclass cannot be overridden in a subclass is written and executed successfully.

