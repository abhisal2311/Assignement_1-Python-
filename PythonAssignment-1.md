## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
Ans.
Python is a general-purpose language which means it can be used for a wide variety of development tasks. It is used to build websites, software, automate task, data analysis. It is versatile and user friendly.


Q2. Why is Python called a dynamically typed language?
Ans.
Python is a dynamically typed language. We don't have to declare the type of a variable or manage the memory while assigning a value to a variable in Python. Other languages like C, C++, Java, etc.., there is a strict declaration of variables before assigning values to them. We have to declare the kind of variable before assigning a value to it in the languages C, C++, Java, etc..,

Python don't have any problem even if we don't declare the type of variable. It states the kind of variable in the runtime of the program. Python also take cares of the memory management which is crucial in programming. So, Python is a dynamically typed language. Let's see one example.


Q3. List some pros and cons of Python programming language?
Ans.
Pros – 
Python is easy to use, read and understand. This feature helps us to save time you can focus on creating solutions rather than focusing on the decrypting the language
Has vast collections of libraries for web development, software development, ML, AI, Video games and many more.
Python is free open source and has vibrant community
Python is portable programming language
 
Cons-
Python has speed limitations, slow processing time.
Not so strong with mobile computing not good for mobile apps.
While using Python , you can expect to see runtime errors because of the dynamical typing feature of this programming language.
Since the data of a variable is not static, it can change at any time, so runtime errors are really hard to avoid. So it goes without saying that as a Python programmer, you should dedicate some time to rigorous testing in order to get the preferred outcome.
Consumes lot of memory space
Python is not easy to test
When your program is being executed, all the errors are caught in the process. And for you to successfully launch the output, you must clear out or modify every single error, so testing takes a lot of time and sweat.






Q4. In what all domains can we use Python?
Ans.

One type of programming language is focused on functions, while the other is focused on real-world data. In the case of Python, though, both functions are possible. Python is also noted for being incredibly adaptable and portable. It means that a programmer can build Python code for Linux or Windows and then use it on iOS and other platforms without having to change the code.

1. Web development
Any business must invest in web development. Python also has a number of business-oriented web development alternatives. Flask, Pyramid, Django, and Bottle are some of the best examples of Python's sophisticated web development frameworks. Furthermore, you will get the opportunity to work with complex content management systems such as Django CMS and Plone.

2. Data science
Python is an excellent tool for creating data-driven solutions. Take Spotify, for example, where it enables the app to provide smooth music streaming with features such as smart radio channels, discover playlists, and so on. Python certification typically teaches how to utilise Python to create data-driven insights, which can be beneficial to businesses.

3. OS development
The Python programming language lies at the heart of a number of operating systems, the bulk of which are Linux distributions. RedHat enterprise's Anaconda installer, Fedora, and Ubuntu's Ubiquity installer are just a few of the popular operating systems.

4. Scientific programming
Python is becoming a popular tool in the field of numerical and scientific computing. Python is useful because it provides a skeleton for programmes that work with scientific and computational data. Python code can be found in programmes like Abaqus and FreeCad. In reality, if you wish to create such useful scientific applications, every developer will advise you to get the greatest Python certification accessible.

5. Gaming
When it comes to interactive game development, Python has a number of modules that are really handy.

PyGame and PySoy, two of the most popular Python libraries, have been widely used in the development of a variety of games.

World of Tanks, Battlefield 2, Disney's Toontown Online, Frets On Fire, Civilization-IV, and Vega Strike are just a few of the notable games that include Python code.

Q5. What are variable and how can we declare them?
Ans.
Variable are containers for storing data values.
Creating variables - Python has no command for declaring a variable. A variable is created the moment you first assign a value to it. Variables do not need to be declared with any particular type, and can even change type after they have been set. Lets see example:
x = 5
y = "John" 
Q6. How can we take an input from the user in Python?
Ans.
Python allows for user input.That means we are able to ask the user for input.
uses the input() method.
The following example asks for the username, and when you entered the username, it gets printed on the screen:
Username = input(“Enter username”)
Print(Username)
Will give you the solution

Q7. What is the default datatype of the value that has been taken as an input using input() function?
Ans.
Python input() function is used to take user input. By default, it returns the user input in form of a string.


Q8. What is type casting?
Ans.
Type Casting is the method to convert the variable data type into a certain data type in order to the operation required to be performed by users. In this article, we will see the various technique for typecasting.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Ans.
You can take multiple inputs in one single line by using the input function several times as shown below.
x, y = input("Enter First Name: "), input("Enter Last Name: ") 
print("First Name is: ", x) 
print("Second Name is: ", y)


Output:
Enter First Name: FACE
Enter Last Name: Prep
First Name is: FACE
Second Name is: Prep

Q10. What are keywords?
Ans.
Python keywords are special reserved words that have specific meanings and purposes and can’t be used for anything but those specific purposes. These keywords are always available—you’ll never have to import them into your code.


Q11. Can we use keywords as a variable? Support your answer with reason.
Ans.
Keywords are some predefined and reserved words in python that have special meanings. Keywords are used to define the syntax of the coding. The keyword cannot be used as an identifier, function, and variable name.




Q12. What is indentation? What's the use of indentaion in Python?
Ans.
Indentation refers to the spaces at the beginning of a code line.
Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important.
Python uses indentation to indicate a block of code.

Q13. How can we throw some output in Python?
Ans.
Python print() function prints the message to the screen or any other standard output device.

Syntax: print(value)

Q14. What are operators in Python?
Ans.
Operators are used to perform operations on variables and values.
In the example below, we use the + operator to add together two values:
Print(10+5)
Python operators divided in following groups
Arithmetic operators
Assignment operators
Comparison operators
Logical operators
Identity operators
Membership operators
Bitwise operators

Q15. What is difference between / and // operators?
Ans.
/ is regular division(returns float) and // is floor division(returns int).

Floor division was introduced in python 3.

eg:

x = 5/2 #2.5 
y = 5//2 #2 
Cheers :)

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
Ans.
x = "iNueron"
print(x * 4)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Ans.
num2 = int(input("Enter your number:"))
if num2 % 2 ==0:
    print(" %s is even" %num2)
else:
    print(" %s is odd" %num2)

Q18. What are boolean operator?
Ans.
The logical operators and, or and not are also referred to as boolean operators. While and as well as or operator needs two operands, which may evaluate to true or false, not operator needs one operand evaluating to true or false.Boolean and operator returns true if both operands return true.

Q19. What will the output of the following?
```
1 or 0 = 1

0 and 0 = 0

True and False and True = False 

1 or 0 or 0 = 0
```

Q20. What are conditional statements in Python?
Ans.
Conditional Statement in Python perform different computations or actions depending on whether a specific Boolean constraint evaluates to true or false, and also it is a decision-making statements in programming languages decide the direction of the flow of program execution.
In Python decision making statements are :
if statement.
if-else statement.
Elif statement.

Q21. What is use of 'if', 'elif' and 'else' keywords?
Ans.
01. if statement :
If statements are control flow statements which helps us to run a particular code only when a certain condition is satisfied. For example, you want to print a message on the screen only when a condition is true then you can use if statement to accomplish this in programming.
If – else:
In simple way, The if-else statement is used to execute both the true part and the false part of a given condition. If the condition is true, the if block code is executed and if the condition is false, the else block code is executed.
The Elif condition is used to include multiple conditional expressions after the if condition or between the if and else conditions. The Elif block is executed if the specified condition evaluates to True . In the above example, the Elif conditions are applied after the if condition.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
Ans.
age = int(input("Enter your age:"))
if age >= 18:
    print("I can vote")
else:
    print("I can't vote")


Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans.
numbers = [12, 75, 150, 180, 145, 525, 50]
sum = 0
for i in numbers:
    if i % 2 == 0:
        sum = sum + i

print("Sum of even number is ", sum)



Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
Ans.
num1 = input("Enter num1 :")
num2 = input("Enter num2 :")
num3 = input("Enter num3 :")

if (num1 >= num2) and (num1 >= num3):
    largest = num1
elif (num2 >= num3 ) and (num2 >= num1):
    largest = num2
else:
    largest = num3
    
print(“Largest number is ”,largest)


Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

Ans.
numbers = [12, 75, 150, 180, 145, 525, 50]

for num in numbers:
        if num > 500:
            break
        if num > 150:
            continue
        if num % 5 == 0:
            print(num)
