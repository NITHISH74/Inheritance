# Inheritance

## Aim:
To write a C# program to print some messages using hierarchical inheritance


## Algorithm:
## Step 1:
Create a base class.

## Step 2:
Create two child class.

## Step 3:
Create a constructor in the base class and print a message.

## Step 4:
create a function in child class to print a message.

## Program:

```
using System;
namespace hello
{
    public class vehicle
    {
        public vehicle()
        {
            Console.Write("Tyre is attached");
        }

    }
    public class car : vehicle
    {
        public void display()
        {
            Console.WriteLine("to car");
        }
    }
    public class scooter : vehicle
    {
        public void display()
        {
            Console.WriteLine("to scooter");
        }
    }
    public class program
    {
        public static void Main(string[] args)
        {
            car car = new car();
            car.display();
            Console.WriteLine();
            scooter scooter = new scooter();
            scooter.display();
            Console.ReadKey();
        }
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/94164665/173244476-8f33b98b-508f-4f79-8ddc-8fdc348db683.png)


## Result:
C# program to print some messages using hierarchical inheritance is implemented successfully.


