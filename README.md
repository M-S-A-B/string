# string



NAME: Mohamad Saad Ansar Bijapuri
PRN: 22070123070


Title:Strings

Aim: To learn Object oriented programming in C++

Theory:C++ strings are sequences of characters stored in a char array. Strings are used to store words and text. They are also used to store data, such as numbers and other types of information. Strings in C++ can be defined either using the std::string class or the C-style character arrays.
1. C Style Strings
These strings are stored as the plain old array of characters terminated by a null character ‘\0’. They are the type of strings that C++ inherited from C language.

Syntax:
char str[] = "string";

2. std::string Class
These are the new types of strings that are introduced in C++ as std::string class defined inside <string> header file. This provides many advantages over conventional C-style strings such as dynamic size, member functions, etc.

Syntax:

std::string str("string");

One more way we can make strings that have the same character repeating again and again.

Syntax:

std::string str(number,character);



Algorithm:

Start =>  declare a string and an integer with value=0 => Take input of name and surname and store in the string => use for loop and if conditional statement to conut the number of characters in the string => keep counting till null vector is reached and keep incrementing the value of the declared integer in every for loop iteration => print number of charaters in the string =>  End


Explanation of the algorithm:
In this code we declare a string and an integer with value=0. Take input of name and surname and store in the string. Use for loop and if conditional statement to conut the number of characters in the string and keep counting till null vector is reached, and also keep incrementing the value of the declared integer in every for loop iteration. Print number of charaters in the string, which is given by the value of the incremented integer.

![image](https://github.com/M-S-A-B/string/assets/140503259/d86806c1-f294-411f-bc0c-03f256f4c417)

![image](https://github.com/M-S-A-B/string/assets/140503259/0eaf1995-e163-48ce-930f-06d952ee8572)

