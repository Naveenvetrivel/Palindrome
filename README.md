# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
## step1
To start the C# program in visual Studio 2022.
## step2
Create a class and declare two variable with string datatype.
## step3
Loop over the entire string and reverse it.
## step4
Use if condition to check whether the string and the reversed string is equal or not.
## step5
print palindrome if it's equal else print not a palindrome.
## step6
Save the program and run the program in visual studio 2022.
## Program:
~~~
using System;
namespace PALINDROME
{
    public class Palindrome
    {
        static void Main(string[] args)
        {
            string word, reverse = "";
            word = Convert.ToString(Console.ReadLine());
            Console.WriteLine("before reverse:" + word);
            for (int i = word.Length - 1; i >= 0; i--)
            {
                reverse += word[i];
            }
            if (reverse == word)
            {
                Console.WriteLine("{0} it is palindrome", reverse);
            }
            else
            {
                Console.WriteLine("{0} its not palindrome", reverse);
            }
            Console.ReadLine();
        }
    }
}
~~~

## Output:
![image](https://github.com/Naveenvetrivel/Palindrome/assets/94165322/960d5a1a-b5c3-4f5c-a903-6b3323d0dd1d)

## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
