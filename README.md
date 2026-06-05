# PSFA
Python scripts for different kinds of projects. technically counts as a lesson lol

the core basics to start in python are readable syntax.

Printing to screen: print() to display text or results instantly
Variables: To store data like numebers (integers, floats) or text (strings) for later use.
Basic math: Python can also be used as a simple calculator with standard operators like +,-,*, and /
User input: Use input() to allow a program interact with a user and take in information
if/Else statements: Simple logic to make decisions, such as "if age > 18:print("Adult")

Python 3.8
How to assign values to variables:
1st you have to input "item =" then Following 'item name' then assign it a value. '' is a string.
Also keep in mind that python is a Kei sensitive language meaning an item with an Big I and an item with a small i will mean 2 completely different things.
A naming convention in python is to add an underscore "_" everytime you have more than one word. For example if we say "Item_name" You would want to add the underscore "_" and if we add orange it will be "Item_name = 'orange'".

Lets make an example to show you why Item with a big I and item with a small i matters. 
If we input the code "item = banana" then input "print(item, Item)" it will print the word banana apple.
                      item = apple
Now lets add another string and this time it will be "print('Hello '+ item_name) and in this case its item_name = Orange, It will print "Hello Orange."

Next up in Python 3.8 is data types. So first of all we have integers. Integer is just any number. If we input "Integer = 2021 or 22023 or any number that number will be highlighted as blue. Then we have strings, as shown earlier it is just any text inside quotation marks. Then we have boolean which is just a simple true or false. and the final one is list. first you want to input angle brackets "[]"then add the values u want to add in the angle brackets. can be a mixture of numbers letters boolean and such,.

Integer: Integer = 2021
String: word = 'text
isMappy = False/True
naughty_list = ['Luigi', 'Mario', 'Toad']
Now if we print them it should say what is being shown after the =

print(Integer)
print(word)
print(isMappy)
print(naughty_list)

Lets move on to an example where we want to input more than 2 different numbers in the code.
integer = 2021
name = 'Mario'
string_number = '22'
If you input it you will notice that 2021 is blue and 22 is green. that is because 22 is considered a text and 2021 is considered an integer. what we need to do is convert them to the correct types before combining them. so to do that we could just put 
"print(name + str(integer))"

Now what we did there is we converted the integer into a string so we could combine Mario and 2021 together (Mario2021). If we remove "str(integer)" we will get an exception saying we can only concentrate str and not "int" to str. the same thing goes to string number.

We now move on to doing math in python. first lets create 2 variables, A = 22 and B = 25. ngl its pretty self explanitory so its,
addition = a + b
difference = a - b
multiply = a * b
divide = a/b
power = a**b

