# Ryannet Dev
## Programming
### Learn C
C is a significant language\
It was used to create the UNIX operating system\
It's quite popular\
So let's get started!
#### C Headers
In every C program, you will see this below at the beginning:\
`#include <stdio.h>`\
Well, this is a line to add header files in which you can use commands the header files have\
`stdio` stands for **S**tandard **I**nput/**O**utput\
Every C Header file has the `*.h` file extension
#### Executing code
After adding the header, we need a place to run code so you can use:\
`int main() {}`
Any code inside the curly brackets (`{}`) will be executed
##### Printing text
To print text, we can use the `printf()` command\
Any text inside the parenthesis (`()`) will be printed\
Custom text should be wrapped in double quotes (`""`)
```C
printf("This will print text");
printf(This will give an error);
```
Also note that every statement must end with a semicolon (`;`)
#### Declaring variables
##### Creating variables
To declare a variable in C, you must use this:\
`Type Name = Value;`
There are four types of variables:
1. Integer (Stores whole numbers)
2. Float (Stores decimal numbers)
3. Double (Stores bigger decimal numbers)
4. Character (Stores single character)
5. String (Stores text)
6. Boolean (Stores true or false
To declare an integer variable:\
`int name = number;`\
To declare a float variable:\
`float name = number.decimal;`\
To declare a double variable:\
`double name = number.decimal;`\
To declare a character variable:\
`char name = 'Character';`\
To declare a string:\
`char name[] = "Text";`\
##### Printing variables
To print an integer variable:\
`printf("%d", integer);`\
`printf("%i", integer);`\
To print a float variable:\
`printf("%f", float);`\
To print a character variable:\
`printf("%c", character);\
To print a string variable:\
`printf("%s", string);`
