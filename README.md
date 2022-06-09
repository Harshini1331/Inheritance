# Inheritance

## Aim:
 To write a C# program to print some messages using hierarchical inheritance.

## Algorithm:
Step 1:
Create a base class.

Step 2:
Create two child class.

Step 3:
Create a constructor in the base class and print a message.

Step 4:
create a function in child class to print a message.

## Program:
```python
using System;
namespace Hello
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
            Console.Write(" to car\n");
        }
    }
    public class scooter : vehicle
    {
        public void display()
        {
            Console.Write(" to scooter\n");
        }
    }
    public class program
    {
        public static void Main(string[] args)
        {
            car car = new car();
            car.display();
            scooter scooter = new scooter();
            scooter.display();
        }
    }
}

```

## Output:
<img width="673" alt="image" src="https://user-images.githubusercontent.com/75235554/172899240-25df6742-1a97-40a1-b1c2-42bca12c272b.png">

## Result
Thus, a C# program to print some messages using hierarchical inheritance was developed successfully.

