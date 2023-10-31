# EX08-Inheritance

## Aim:

To write a C# program to print some messages using hierarchical inheritance.

## Algorithm:

step 1: Create a base class.

Step 2: Create two child class.

step 3: Create a constructor in the base class and print a message.

step 4: create a function in child class to print a message.

## Program:

Name : HARITHA SHREE.V

Reg.no: 212222230046
```python
using System;
namespace inheritance
{
    public class tyre
    {
        public virtual void display()
        {
            Console.Write("Tyre is attached to: ");
        }
    }

    public class car : tyre
    {
        public override void display()
        {
            base.display();
            Console.WriteLine("Car");
        }
    }

    public class scooter : tyre
    {
        public override void display()
        {
            base.display();
            Console.WriteLine("Scooter");
        }
    }
    public class main
    {
        public static void Main(string[] args)
        {
            car c = new car();
            c.display();
            Console.WriteLine();
            scooter s = new scooter();
            s.display();
        }
    }
}
```


## Output:

![image](https://github.com/haritha-venkat/Inheritance/assets/121285701/675aab37-d3b2-4f95-95b9-4c87e0ee1379)


## Result:
Thus C# program to print some messages using hierarchical inheritance is written and executed sucessfully.


