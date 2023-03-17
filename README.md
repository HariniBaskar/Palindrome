# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.

## Algorithm:
Step1: Start

Step2: Create a class and declare two variable with string datatype

Step3: Loop over the entire string and reverse it

Step4: Use if condition to check whether the string and the reversed string is equal or not

Step5: Print palindrome if it's equal else print not a palindrome.

Step6: End the program

## Program:
```
Developed by: Harini.B
Register Number: 21221230035
```
```
using System;
namespace exp2
{
    class Program
    {
        static void Main(string[] args)
        {
            string s, rev = "";
            Console.WriteLine(" Enter string");
            s = Console.ReadLine();
            for (int i = s.Length - 1; i >= 0; i--)
            {
                rev += s[i];
            }
            if (rev == s)
            {
                Console.WriteLine("{0} is Palindrome", s);
            }
            else
            {
                Console.WriteLine("{0} is not Palindrome", s);
            }
        }
    }
}
```

## Output:
### PALINDROME 
![image](https://user-images.githubusercontent.com/93427253/225878597-8f9d7ae6-4f80-4b7b-b55f-42d6303b41a9.png)
### NOT A PALINDROME
![pal2](https://user-images.githubusercontent.com/93427253/225879205-0a8568e0-16ac-4db4-9fc4-08385e28c22c.png)


## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
