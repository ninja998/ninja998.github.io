---
layout: post
title: Variables
categories: C# Programming
---

 ```csharp
 Console.WriteLine("Enter the number of centimetres:");
 double cm = Convert.ToDouble(Console.ReadLine());
 double feet;
 feet = cm / 30.48;
 Console.WriteLine(cm + " centimetres is the same as " + feet + "feet.");
 Console.ReadLine();
 ```
            
 This code converts a given number of centimetres that can even have decimals and convert it into feet.
 It does this by using variables which can be used to store a value, however first you must assign it a
 data type. In this example i use a double, which allows it to be a decimal for accuracy reasons. For a 
 program like this you wouldnt want to use an int because it would make it much less accurate.
