---
layout: post
title: If Statements
categories: C# Programming
---
 
```csharp
Console.WriteLine("what is the value of a");
            double a = Convert.ToDouble(Console.ReadLine());
            Console.WriteLine("what is the value of b");
            double b = Convert.ToDouble(Console.ReadLine());

            if (a==b)
            {
                Console.WriteLine("A is the same as B");
            }
        else if (a>b)
            {
                Console.WriteLine("A is bigger than b");
            }
        else if (a<b)
            {
                Console.WriteLine("a is smaller than b");
            }
            Console.ReadLine();
```
 
 This Code compares the size of 2 numbers and tells you which one is bigger. It does this by using if statements to repeatadly put the two
 numbers through operations to see what the result is and then it outputs the information for the user.
