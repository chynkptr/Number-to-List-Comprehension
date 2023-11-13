•	Section 1 is compulsory
•	Select any one from Section 2 and Section 3
•	Select any one from Section 4 and Section 5
•	Open Book Exam
•	Comment your code 
•	Use of Jupyter Notebook is allowed
•	Upload your Jupyter notebook file on Mettl and BB

```python
1+1
```




    2




```python
2+3
```




    5




```python
5+5
```




    10




```python
5+2
```




    7




```python
#Comment line is required in the exam
```


```python
5+2
```




    7




```python
5.1
```


```python
5
```


```python
4+2
```




    6




```python
4-2
```




    2




```python
5*2
```




    10




```python
10/2
```




    5.0




```python
10//2
```




    5




```python
7//2
```




    3




```python
2*3 = 6 (remainder is 7)
qoutient is 3 
```


```python
7%2
```




    1




```python
9%2
```




    1




```python
8%2
```




    0




```python
7%4
```




    3




```python
2**4
```




    16




```python
5**3
```




    125




```python
4**0.5
```




    2.0




```python
2+10*10+3 #BODMAS
```




    105




```python
(9*10)+(6*7)
```




    132




```python
5a is invalid 
a 5 is invalid
a_5 is valid 
```


```python
do not use keywords/special meaning words as a variable names 
int = 5 (invalid)
str = 'hello'(invalid)
```


```python
a = "hello"
len(a)
```




    5




```python
a=5  #Variable
b=6
a+b
```




    11




```python
a+a
```




    10




```python
a=a+a
```


```python
a+b
```




    26




```python
a+a+b
```




    46




```python
a = 'hello'
a
```




    'hello'




```python
len(a)
```




    5




```python
name = 'yani'
name
```




    'yani'




```python
print('Welcome',name,'to ICP clasa')
```

    Welcome England to ICP clasa
    


```python
mystr= '1234'
```


```python
mynum = 1234
```


```python
mystr = "1234"
(type(mystr)) 
```




    str




```python
type(mynum)
```




    int




```python
mynum = 1234
(type(mynum))  
```




    int




```python
mynum = int(input("Enter the number:"))
print(mynum)
```

    Enter the number:9
    9
    


```python
mynum = float(input("Enter the number:"))
type(mynum)
```

    Enter the number:8
    




    float




```python
mynum
```


```python
city = input("Enter the city name:")
```

    Enter the city name:Jakarta
    


```python
city = 'Jakarta'
len(city)
```




    7




```python
name = 'England'
len(name)
```




    7




```python
len("yani")
```




    4




```python
a = "hello"
len(a)
```




    5




```python
a = "hello"
a[0]
```




    'h'




```python
a[1]
```




    'e'




```python
a[0:2]
```




    'he'




```python
a = "hello"
a[1:2]
```




    'e'




```python
a[-1]
```




    'o'




```python
a[0:4]
```




    'hell'




```python
a[0:-1]
```




    'hell'




```python
am ="abcdef"
am = am[::-1]
```


```python
a = "abcdef"
a = a[::-1]
print(a)
```

    fedcba
    


```python
a[1:-1]
```




    'edcb'




```python
a[0:3]
```




    'fed'




```python
a[:]
```




    'hello'




```python
a[-1]
```




    'o'




```python
a[-2]
```




    'l'




```python
a[-4]
```




    'e'




```python
a[-5]
```




    'h'




```python
a[-3]
```




    'l'




```python
s ='abcde'
s[1:3]
```




    'bc'




```python
s[0:4]
```




    'abcd'




```python
s = def
```


      Cell In[31], line 1
        s = def
            ^
    SyntaxError: invalid syntax
    



```python
s[3:]
```




    'de'




```python
s[0:5:2]
```




    'ace'




```python
a[:]
```




    'hello'




```python
s[::]
```




    'abcde'




```python
s[::-1]
```




    'edcba'




```python
s[::-2]
```




    'eca'




```python
s[0:5]
```




    'abcde'




```python
#string indexing 
```


```python
a="hello"
b="world"
a+b
```




    'helloworld'




```python
a+" "+b
```




    'hello world'




```python
a="Yani"
a+a
```




    'YaniYani'




```python
a*3
```




    'YaniYaniYani'




```python
+ ... concat
* ... replication

```


```python
#STRINGS are immutable 
```


```python
f ="Sydney"
S[0] = "K"
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    Cell In[25], line 2
          1 f ="Sydney"
    ----> 2 S[0] = "K"
    

    NameError: name 'S' is not defined



```python
f="Sydney"
"K" + f[1:]
```




    'Kydney'




```python
l="Hello"
"C"+l[1:]
```




    'Cello'




```python
print(l)
```

    Hello
    


```python
l
```


```python
f[0]
```




    'S'




```python
f[1:]
```




    'ydney'




```python
f[0]+f[1:]
```




    'Sydney'




```python
f
```




    'Sydney'




```python
d = "Hello World" 
d.upper()
```




    'HELLO WORLD'




```python
parathesis ()-round bracket 
```


```python
d = "Hello World"
d = d.lower()
print(d)
```

    hello world
    


```python
d ="Hello World"
d.lower() #do not use islower or isupper 
```




    'hello world'




```python
d.replace("o","a")
```




    'Hella Warld'




```python
Numbers(Integers, float)
Strings 
```


```python
h ="Hello World"
h.split()
```




    ['Hello', 'World']




```python
h ="hello,world"
h.split()

```




    ['hello,world']




```python
h ="hello,world"
h.split(',')
```




    ['hello', 'world']




```python
n = "sa pi yo"
n.split()
```




    ['sa', 'pi', 'yo']




```python
k = "na-ni-nu"
k.split("-")
```




    ['na', 'ni', 'nu']




```python
a = int(input('Enter your name:'))
print("Welcome",a, "to the course")
```

    Enter your name:Yani
    


    ---------------------------------------------------------------------------

    ValueError                                Traceback (most recent call last)

    Cell In[27], line 1
    ----> 1 a = int(input('Enter your name:'))
          2 print("Welcome",a, "to the course")
    

    ValueError: invalid literal for int() with base 10: 'Yani'



```python
a = input('Enter your name:')
print("Welcome", a, "to the course")
```

    Enter your name:Yani
    Welcome Yani to the course
    


```python
y = 20
n = 21
y+n
```




    41




```python
y*n
```




    420




```python
j ="introduction to computer programming"
j.title()
```




    'Introduction To Computer Programming'




```python
a = int(input("Enter the number:"))
b = int(input("Enter the number:"))
print("The sum of 2 numbers is", a+b)
print("The product of 2 numbers is", a*b)
```

    Enter the number:7
    Enter the number:9
    The sum of 2 numbers is 16
    The product of 2 numbers is 63
    


```python
a = "hello"
b = "dam"
print(a[::-1])
print(b[::-1])
```

    olleh
    mad
    


```python
a = input('Enter the word: ')#user input the string 1
b = input('Enter the word:')#user input the string 1
print(a[::-1],b[::-1])#for reversing the string 
```

    Enter the word: hello
    Enter the word:mad
    olleh dam
    


```python
s= "UCDS"
type(s)
```




    str




```python
s.lower()
```




    'ucds'




```python
#lower, upper, capitalize, split.... len(), type()
```


```python
#Comparison operators
```


```python
s= "UCDS"
type(s)
```

    21
    


```python
a
```




    21




```python
a==b #is value of a is equal tobe 
```




    True




```python
a=5
b=6
a!=b
```




    True




```python
1!=4
```




    True




```python
1==5
```




    False




```python
1<5
```




    True




```python
2<=7
```




    True




```python
5>=9
```




    False




```python
10>8
```




    True




```python
4>11
```




    False




```python
#Chained Operator
```


```python
2<3 and 5>2
```




    True




```python
5<2 and 7<9
```




    False




```python
9<2 or 7>3
```




    True




```python
6<2 or 7>9
```




    False




```python
3 >= 3
```




    True




```python
2<=2
```




    True




```python
4<=2
```




    False




```python
#Conditional Statement
```


```python
100==100 or 99==99
```




    True




```python
a=5
print("a is equal to 5")
print("a is unequal to 5")
```


```python
a=5

if a==5:
    print("a is equal to 5")
else:
    print("a is unequal to 5")
```

    a is equal to 5
    


```python
a=int(input("Enter the number:"))

if a>6:
    print("A is greater than 6")
else: 
    print("A is less than 6")
```

    Enter the number:8
    A is greater than 6
    


```python
a = int(input("Enter the number:"))

if a == 9:
    print("a is equal to 9")
elif a >= 9:
    print("a is greater than or equal to 9")
else:
    print("a is less than 9")
```

    Enter the number:9
    a is equal to 9
    


```python
x=int(input("Enter the value of x:"))
y=int(input("Enter the value y:"))

if x==y:
    print("Both are equal")
else:
    print("Both are unequal")
```

    Enter the value of x:9
    Enter the value y:8
    Both are unequal
    


```python
x= 9
y= 9

if x==y:
    print("Both are equal")
else:
    print("Both are unequal")
```

    Both are equal
    


```python
x = "Yani"
y = "Inay"

if x==y:
    print("Both are equal")
else:
    print("Both are unequal")
```

    Both are unequal
    


```python
#Indentation - Phyton
```


```python
name = input("Enter the name:") #Ask the user to input his name
x= "John"#The value of x is John

if name==x: #If the name is equal to John x
    print("You are John") #Print that he is Johm
else: #If the name is not equal to John
    print("You are not John") #Print that he is not John
```

    Enter the name:john
    You are not John
    


```python
name = input("Enter the name:") #Ask the user to input his name

if name=="John": #If the name is equal to John x
    print("You are John") #Print that he is Johm
else: #If the name is not equal to John
    print("You are not John") #Print that he is not John
```

    Enter the name:John
    You are John
    


```python
name = input("Enter the name:") #Ask the user to input his name

if name=="John": #If the name is equal to John x
    print("You are John") #Print that he is John
elif name=="john": #If the input equal to name but in the lowercase letters 
    print("You are still John")
else: #If the name is not equal to John
    print("You are not John") #Print that he is not John
```

    Enter the name:John
    You are John
    


```python
x = int(input("Write the number x:"))#Ask the user to input x's value
y = int(input("Write the number y:"))#Ask the user to input y's value

if x>y: #if the input of x is greater than input of y 
    print("x is greater than y") #Print that x is greater than y 
elif x==y: #if the input of x is equal to the input of y
    print("Both are equal")#print that x and y are equal
else: #otherwise the value of x is less than the value of y 
    print("x is less than y") #print that x is less than y 
```

    Write the number x:10
    Write the number y:9
    x is greater than y
    


```python
celcius = int(input("Enter the temperature in Celcius:"))#Ask the user to input the temperatire in celcius

if celcius<10:#if the temperature is less than 10  degree celcius
    print("Wow, right now is colder")#print today is colder
elif celcius==10:#if the temperature is equal to 10 degree celcius 
    print("Well, the temperature is balance")#print today temperature is balance
else:#otherwise, if the temperature surpassed 10 degree celcius
    print("Today is HOT")#print that today is hot
```

    Enter the temperature in Celcius:36
    Today is HOT
    


```python
a = int(input("Enter the number:"))

if a<=25:
    print("The temperature is balance")
elif a>10 and a<=25:
    print("Today is warm")
else:
    print("The temperature is totally hot")
```


```python
a=input("Write the name:")#Ask the user to input the name John or admin

if a=="John":#If the username is John
    print("Welcome",a, "to the room")#Print to greet John
elif a=="admin":#If the username is admin
    print("Welcome",a, "to the room")#print to greet admin
else:#While if it is not John or Admin
    print("Sorry, you are not John or an admin")#Print to give rejection
```

    Enter the number:11
    The temperature is balance
    


```python
a=input("Write the name:")#Ask the user to input the name John or admin

if a=="John":#If the username is John
    print("Welcome",a, "to the room")#Print to greet John
elif a=="admin":#If the username is admin
    print("Welcome",a, "to the room")#print to greet admin
else:#While if it is not John or Admin
    print("Sorry, you are not John or an admin")#Print to give rejection
```

    Write the name:inay
    Sorry, you are not John or an admin
    


```python
a=input("Write the name:")#Ask the user to input the name John or admin

if a.lower() =="john":#If the username is John,JOHN,john,etc.
    print("Welcome",a, "to the room")#Print to greet John,john,JOHN, etc.
elif a.lower() =="admin":#If the username is admin,ADMIN,etc.
    print("Welcome",a, "to the room")#print to greet admin,ADMIN,etc.
else:#While if it is not John or Admin
    print("Sorry, you are not John or an admin")#Print to give rejection
```

    Write the name:jOHN
    Welcome jOHN to the room
    


```python
a=input("Write the name:")#Ask the user to input the name 

if a.upper() =="JOHN":#If the username is John,JOHN,john,etc.
    print("Welcome",a, "to the room")#Print to greet John,john,JOHN, etc.
elif a.upper() =="ADMIN":#If the username is admin,ADMIN,etc.
    print("Welcome",a, "to the room")#print to greet admin,ADMIN,etc.
else:#While if it is not John or Admin
    print("Sorry, you are not John or an admin")#Print to give rejection
```

    Write the name:JOhn
    Welcome JOhn to the room
    


```python
name = input("Enter your name:")
if "john" in name.lower():
    print("Welcome John")
else:
    print("invalid user")

```

    Enter your name:JOHN
    Welcome John
    


```python
a = input("Write the name:")#Ask the users to enter the name

if a.upper()==a[::-1]:#If they write down a palindrome in uppercase
    print("This is a palindrome")#print to proof it is a palindrome
elif a.lower()==a[::-1]:#If they write down a palindrome in lowercase
    print("This is also a palindrome")#print to proof it is a palindrome
else:#if it is not a palindrome
    print("Not a palindrome")#print to proof it's not a palindrome 
```

    Write the name:Eve
    Not a palindrome

a = input("Write the name:")  # Ask the users to enter the name

a = a.lower()  # Convert the input to lowercase for consistency

if a == a[::-1]:  # Check if the lowercase input is a palindrome
    print("This is a palindrome")  # Print to show it is a palindrome
else:
    print("Not a palindrome")  # Print to show it's not a palindrome



```python
a=5 #Variable a is 5
b=6 #Variale a is 6

b=a+b  #to sum a and b to get the value of b
a=b-a #substracting a from b, assigining it to b, giving the value of a
b= b-a#substracting from b, assigining it to b, giving the value of b
print("a = ",a) #print a is equal to 6
print("b = ",b) #print a is equal to 5
```

    a =  6
    b =  5
    


```python
1. Swap 2 numbers 
```


      Cell In[3], line 1
        1. Swap 2 numbers
           ^
    SyntaxError: invalid syntax
    



```python
#Method 1
a = 5  # Assign the value 5 to variable 'a'.
b = 6  # Assign the value 6 to variable 'b'.

# Swap the values of 'a' and 'b using a temporary variable.
temp = a  # Create a temporary variable 'temp' and store the value of 'a' in it.
a = b     # Assign the value of 'b' to 'a', so 'a' now becomes 6.
b = temp  # Assign the value stored in 'temp' (which is the original value of 'a') to 'b', so 'b' becomes 5.

# Print the final values of 'a' and 'b after the swap.
print("a =", a)  # Display the value of 'a'.
print("b =", b)  # Display the value of 'b'.

```

    a = 6
    b = 5
    


```python
#Method 2 (not using temp)
a=5 #Assign the value of a to b
b=6 #Assign the value of a to b

a=a+b #Assign a to the summation of the value a and b
b=a-b #Assign b to the subtraction the new value of a and  previous value of b
a=a-b##Assign a to the subtraction the new value of b and  previous value of a


print("a=",a)#Generate to print the value of a
print("b=",b)#Generate to print value of b
```

    a= 6
    b= 5
    


```python
#Method 3 
# Swap the values of variables 'a' and 'b' using a tuple assignment.
a = 5  # Initialize 'a' with the value 5.
b = 3  # Initialize 'b' with the value 3.

# Use a tuple assignment to swap the values of 'a' and 'b.
a, b = b, a  # 'a' will now hold the value of 'b', and 'b' will hold the value of 'a'.

# Print the updated values of 'a' and 'b after the swap.
print("a =", a)  # Display the value of 'a' (which is now 3).
print("b =", b)  # Display the value of 'b' (which is now 5).
```

    a = 3
    b = 5
    


```python
#Check if the number odd or even
#%2==0 to check this an odd or an even number 

a = int(input("Enter the number:"))  # Ask the user to enter a number

if a == 0:
    print("The value is zero")  # Display that the value is zero
elif a % 2 == 0:
    print("The value is an even number")  # Display that the value is an even number
else:
    print("The value is an odd number")  # Display that the value is an odd number
```

    Enter the number:1
    The value is an odd number
    


```python
for a in range(1, 4):  # Loop for the increasing part
    print("* " * a)  # Print '*' repeated 'a' times with a space

for a in range(2, 0, -1):  # Loop for the decreasing part
    print("* " * a)  # Print '*' repeated 'a' times with a space
```

    * 
    * * 
    * * * 
    * * 
    * 
    


```python
year= 1990

if year%4==0:
    print("This is a leap year")
else:
    print("False")
```

    False
    


```python
a = int(input("Enter the number 1:"))
b = int(input("Enter the number 2:"))
c = int(input("Enter the number 3:"))
max = a

if b>max:
    max= b
    print("The biggest number is", max)
if c>max:
    max=c
    print("The biggest number is", max)
else:
    print("There are 2 the biggest numbers")
```

    Enter the number 1:1
    Enter the number 2:5
    Enter the number 3:5
    The biggest number is 5
    There are 2 the biggest numbers
    


```python
a = int(input("Enter the number 1:")) #Ask the user to write the value of a
b = int(input("Enter the number 2:")) #Ask the user to write the value of b
c = int(input("Enter the number 3:")) #Ask the user to write the value of c

if a>b and a>c:#If a greater than c and a greater than b
    print("The biggest number is", a)#Give a proof that the biggest number is a 
elif b>a and b>c:#If b greater than a and b greater than c
    print("The biggest number is", b)#Give a proof that the biggest number is b
elif c>a and c>b:#If c greater than a and 
    print("The biggest number is", c)#Give a proof that the biggest number is v
```


```python
#Operators
in 
not in

```


```python
#LIST
```


```python
my_s1=[1,2,3,4,5]
my_s2=['a','b','c','d','e']
s1=int(input("Enter the number:"))
s2=input("Enter the letter:")

if s1 in my_s1:
    print("This number is exist")
if s2 in my_s2:
    print('This letter is exist')
else:
    print("Not exist")
```

    Enter the number:1
    Enter the letter:n
    This number is exist
    Not exist
    


```python
vowels = ["a","i","u","e","o"]
character = input("Enter the letter:")

if character in vowels:
    print("This is a vowel")
else:
    print("This is not a vowel")
```

    Enter the letter:q
    This is not a vowel
    


```python
vowels = ["a","i","u","e","o"]
character = input("Enter the letter:")

if character in vowels:
    print("This is a vowel")
elif character.lower() in vowels: #If vowels are in capital and dont forget to put the parthesis () after the function
    print("This is also a vowel")
else:
    print("This is not a vowel")
```

    Enter the letter:E
    This is also a vowel
    


```python
#LOOP
#repeated in loops
#for loops 
range(1,10)
start-1
end(10-1=9)

range(10)
start-0
end(10-1=9)

range(0,10,2) #print the even numbers
0
2
4
6
8
range(5,10,2)#print the odd numbers
5
7
9

```


```python
#print number 1-10

for i in range(1,11): #using for to assign the range 1 and 11 minus 1
    print(i) #indentation
```

    1
    2
    3
    4
    5
    6
    7
    8
    9
    10
    


```python
for i in range(5,10,2):
    print(i)
```

    5
    7
    9
    


```python
for i in range(1,10,2):
    print(i)
```

    1
    3
    5
    7
    9
    


```python
for i in range(10):
    print(i)
    print('Bye')
```

    0
    Bye
    1
    Bye
    2
    Bye
    3
    Bye
    4
    Bye
    5
    Bye
    6
    Bye
    7
    Bye
    8
    Bye
    9
    Bye
    


```python
for i in range(10):
    print(i)#only this statement is indented
    
print('Bye')
```

    0
    1
    2
    3
    4
    5
    6
    7
    8
    9
    Bye
    


```python
for i in range(10):
    print(i)#only this statement is indented
    
print('i')
```

    0
    1
    2
    3
    4
    5
    6
    7
    8
    9
    i
    


```python
for i in range(10):
    print(i)#only this statement is indented
    
print(i) #inddnted and double print last value 
```

    0
    1
    2
    3
    4
    5
    6
    7
    8
    9
    9
    


```python
for i in range(10):
    print(i) # onlythis statement is indented
    
    print(i)
```

    0
    0
    1
    1
    2
    2
    3
    3
    4
    4
    5
    5
    6
    6
    7
    7
    8
    8
    9
    9
    


```python
vowel="a"
type(vowel)
```




    str




```python
a= 1,2,3
type(a)
```




    tuple




```python
r=[1,2,3]
type(r)
```




    list




```python
f=2
type(f)
```




    int




```python
for i in range(1,6):
    print("hello")
```

    hello
    hello
    hello
    hello
    hello
    


```python
for i in range(1,10,2):
    print(i)
```

    1
    3
    5
    7
    9
    


```python
for i in range(1,11):
    print(i*2)
```

    2
    4
    6
    8
    10
    12
    14
    16
    18
    20
    


```python
for i in range(1,11):
    print(i,"*",2,"=",1*2)
```

    1 * 2 = 2
    2 * 2 = 2
    3 * 2 = 2
    4 * 2 = 2
    5 * 2 = 2
    6 * 2 = 2
    7 * 2 = 2
    8 * 2 = 2
    9 * 2 = 2
    10 * 2 = 2
    


```python
for i in range(1,11):
    print(3,"*",i,"=",1*3)
```

    3 * 1 = 3
    3 * 2 = 3
    3 * 3 = 3
    3 * 4 = 3
    3 * 5 = 3
    3 * 6 = 3
    3 * 7 = 3
    3 * 8 = 3
    3 * 9 = 3
    3 * 10 = 3
    


```python
a=int(input("Enter the value:"))
for i in range(1,11):
    print(a,"*",i,"=",1*a)
```

    Enter the value:5
    5 * 1 = 5
    5 * 2 = 5
    5 * 3 = 5
    5 * 4 = 5
    5 * 5 = 5
    5 * 6 = 5
    5 * 7 = 5
    5 * 8 = 5
    5 * 9 = 5
    5 * 10 = 5
    


```python
for i in range(1, 4):
    print("*" * i)
    
for i in range(2, 0, -1):
    print("*" * i)
```

    *
    **
    ***
    **
    *
    


```python
for a in range(1, 4):  # Loop for the increasing part
    print("* " * a)  # Print '*' repeated 'a' times with a space

for a in range(2, 0, -1):  # Loop for the decreasing part
    print("* " * a)  # Print '*' repeated 'a' times with a space
```

    * 
    * * 
    * * * 
    * * 
    * 
    


```python
#COLLECTION
```


```python
s="hello"

for c in s:
    print(c)
```

    h
    e
    l
    l
    o
    


```python
list1=1,2,3,4

for c in list1:
    print(c)
```

    1
    2
    3
    4
    


```python
list3=["y","a","n","i"]

for c in list3:
    print(c)
```

    y
    a
    n
    i
    


```python
list4=["hello","cahyani","karunia","putri","!"]

for c in list4:
    print(c)
```

    hello
    cahyani
    karunia
    putri
    !
    


```python
t1=(1,2,3,4,5)

for x in t1:
    print(x)
```

    1
    2
    3
    4
    5
    


```python
c="PHYTON"
for s in c:
    print(s)
```

    P
    H
    Y
    T
    O
    N
    


```python
lower case -> uppercase
upper case - > lowercase

PyThOn -> pYtHoN

islower() - > .upper()
isupper() - > .lower()
```


```python
s = "PHYTON"

for c in s:
    print(c.lower())
```

    p
    h
    y
    t
    o
    n
    


```python
s =["P","H","Y","T","O","N"]

for c in s:
    print(c.lower())
```

    p
    h
    y
    t
    o
    n
    


```python
s = "PyThOn"
for i in s:
    if i.isupper(): #dont forget to use parathesis
        print(i.lower())#inside parathesis as well
    else:
        print(i.upper())
```

    p
    Y
    t
    H
    o
    N
    


```python
s= input("Enter the string:")
for i in s:
    if i.isupper():
        print(i.lower())
    else:
        print(i.upper())
```

    Enter the string:Introduction To Computer Programming 
    i
    N
    T
    R
    O
    D
    U
    C
    T
    I
    O
    N
     
    t
    O
     
    c
    O
    M
    P
    U
    T
    E
    R
     
    p
    R
    O
    G
    R
    A
    M
    M
    I
    N
    G
     
    


```python
s = input("Enter the string:")
newwords = ""
for i in s:
    if i.islower():
        newwords += i.upper()
    elif i.isupper():
        newwords += i.lower()
    else:
        newwords += i
print(newwords)        
```

    Enter the string:Introduction To Computer Programming
    iNTRODUCTION tO cOMPUTER pROGRAMMING
    


```python
s = input("Enter the string:")

for i in s:
    if i.isupper():
        print(i.lower(), end='')
    else:
        print(i.upper(), end='')

# Add a new line at the end for better formatting
print()
```

    Enter the string:Introduction To Computer Programming
    iNTRODUCTION tO cOMPUTER pROGRAMMING
    


```python
s = input("Enter the string:") #Ask the use to write the input "Introduction To Computer Programming"
a="" #Empty string 
for i in s: #Iteration through each character in the input "s"
    if i.islower(): #Lowercase letter 
        a += i.upper() #Convert lowercase to the uppercase and string
    elif i.isupper(): #Uppercase letter 
        a += i.lower() #Convert lowercase to the lowercase and string
    else:
        a += i#If it is not a letter, just convert as a string
print(a) #Generate string 
```

    Enter the string:Introduction To Computer Programming
    iNTRODUCTION tO cOMPUTER pROGRAMMING
    


```python
mylist = [1990,2000,2012,2004,2024,2003,2002]
leapyears = [i for i in mylist if (i%4==0 and i %100 != 0) or (i %400==0)]
print(leapyears)
```

    [2000, 2012, 2004, 2024]
    


```python
s= "hello"
a=0
for c in s:
    a= a+1
print(a)
```

    5
    


```python
s="12345"#this is a string
a=0
for c in s:
     a+= int(c)
print(a)
```

    15
    


```python
s="12345"#this is a string
a=0
for c in s: 
     a = a + int(c) #    In the first iteration, c is "1", so int(c) is 1 and and becomes 0 + 1, which is 1 and so on.
print(a)
```

    15
    


```python
s="505"#this is a string
a=0
for c in s: 
     a = a + int(c) #    In the first iteration, c is "5", so int(c) is 1 and becomes 0 + 1, which is 1 and so on.
print(a)
```

    10
    


```python
1.For lopp
2. While loop

```


```python
i=1
while i<10:
    print(i)
    i=i+1 #in the while loop, don't forget to write the summation, otherwise the output printing infinitly
```

    1
    2
    3
    4
    5
    6
    7
    8
    9
    


```python
i=0 #for even numbers
while i<10:
    print(i)
    i+=2
```

    0
    2
    4
    6
    8
    


```python
i=1 #for odd numbers
while i<10:
    print(i)
    i += 2
```

    1
    3
    5
    7
    9
    


```python
i=2 #for even numbers
while i<10:
    print(i)
    i += 2
```

    2
    4
    6
    8
    


```python
i=1 #for odd numbers
while i<10:
    print(i)
    i += 1
```

    1
    2
    3
    4
    5
    6
    7
    8
    9
    


```python
i=2 #for odd numbers
while i<10:
    print(i)
    i += 1
```

    2
    3
    4
    5
    6
    7
    8
    9
    


```python
i=0 #for odd numbers
while i<10:
    print(i)
    i += 1
```

    0
    1
    2
    3
    4
    5
    6
    7
    8
    9
    


```python
i = 0
while i <=10:#10 is exist as well
    print(i)
    i=i+1     # i+=1 
    
```

    0
    1
    2
    3
    4
    5
    6
    7
    8
    9
    10
    


```python
# Write program to input n numbers ... till the user input 0 from the user and print the sum of the numbers

5
3
2

Output: (5+3+2) = 10
    
While loop

5
3
2
0

(5+3+2) = 10  
```


```python
mysum = 0 #Accumulator
while True: #Telling Phyton to run this loop forever (encounter break)
    x= int(input("Enter the number:")) #Ask the user to enter the number
    mysum = mysum + x #The summation will keep the numbers multiple time 
    if x==0:  #If the user write "0", the code must be break/stop and don't forget the use (:)
        break  #Stop the loop running and should make double space
    
print("The sum is:", mysum) #The total of the numbers are written is mysum
```

    Enter the number:5
    Enter the number:3
    Enter the number:2
    Enter the number:0
    The sum is: 10
    


```python
# write program that will ask the user to input a number
# Check if the number is odd or even
# Continue to the user enters a negative number (-1)
# Assume only numbers are entered by the user


Input 

4
Even
5
Odd
16
Even
-3

# ?  : 

```


```python
while True: #Infinite loop 
    
    x= int(input("Enter the number:")) #Ask the user to jot down the number 
    if x<0: #If x is a negative number 
        break #stop the loop
    elif x %2==0: #if x is equal to an even number  and num modulo 2
        print("This is an even number") #give a proof that the value is an even number 
    else: #if x is equal to an odd number 
        print("This is an odd number") #Give a proof tha the value is an odd number
```

    Enter the number:2
    This is an even number
    Enter the number:3
    This is an odd number
    Enter the number:-1
    


```python
mysum = 0 #Accumulator 
while True: #Telling the phyton to run this loop forever (encounter break)
    x= int(input("Enter the number:")) #Ask the user to write the number
    mysum = mysum + x  #The summation will keep the numbers mutiple time until it get zero, the code will stop
    
    if x<0: # if the value of x is negative and remember to keep this firstly and in order 
        break #stop the loop
    if x %2==0: #if the the value of x is equal to odd or even number
        continue #keep the value and keep the loop running 

print("The sum is:",mysum) #the total of value is mysum
```

    Enter the number:2
    Enter the number:3
    Enter the number:0
    Enter the number:-1
    The sum is: 4
    


```python
#break - to stop the loop
#continue/skip
#pass-place holder 
```


```python
x = 0  # Initialize x to 0

while x < 10:
    x = x + 1  # Increment x by 1 in each iteration

    if x == 5:
        continue  # Continue to the next iteration if x is 5
    else:
        print(x)  # Print the value of x if it's not 5
```

    1
    2
    3
    4
    6
    7
    8
    9
    10
    


```python
x = 0  # Initialize x to 0

while x <= 50:
    x = x + 1  # Increment x by 1 in each iteration

    if x % 3 == 0:
        continue  # Continue to the next iteration if x is divisible by 3
    else:
        print(x)  # Print the value of x if it's not divisible by 3
```

    1
    2
    4
    5
    7
    8
    10
    11
    13
    14
    16
    17
    19
    20
    22
    23
    25
    26
    28
    29
    31
    32
    34
    35
    37
    38
    40
    41
    43
    44
    46
    47
    49
    50
    


```python
for x in range(1, 51): #to write a row starting from 1 to 50
    if x % 3 == 0: #if the value of is divisble by 3
        continue  # Skip this iteration if x is divisible by 3
    print(x)#generate 1 to 50 without the number divisble by 3
```

    1
    2
    4
    5
    7
    8
    10
    11
    13
    14
    16
    17
    19
    20
    22
    23
    25
    26
    28
    29
    31
    32
    34
    35
    37
    38
    40
    41
    43
    44
    46
    47
    49
    50
    


```python
print("Hello World")
print("Programming in Python")
```

    Hello World
    Programming in Python
    


```python
# Functions (subprograms ) ... .pass 
```


```python
print("hello","world",sep="$")
```

    hello$world
    


```python
print(1,2,3)
```

    1 2 3
    


```python
sep-seperator 
```


```python
print("hello", end="")
print("world")
```

    helloworld
    


```python
#PATTERN PRINTING 
```


```python
for x in range(1, 6): #to write a row starting point from 1 to 5 
    print("* "*x) #print the * from 1 to 5
```

    * 
    * * 
    * * * 
    * * * * 
    * * * * * 
    


```python
for x in range(1, 6): #to write a row starting from 1 to 5
    print("*"*x)
```

    *
    **
    ***
    ****
    *****
    


```python
*
* *
* * *
* * * * 
* * * * * 
```


```python
# Print the upper part of the pattern, starting from 1 to 3 
for i in range(1, 4):
    print("* " * i)  # Print '*' repeated 'i' times with a space

# Print the lower part of the pattern, starting from 2 to 1 
for i in range(2, 0, -1):
    print("* " * i)  # Print '*' repeated 'i' times with a space
```

    * 
    * * 
    * * * 
    * * 
    * 
    


```python
for i in range(3,0,-1): #Print upper part start from 3 to 1
    print("* "*i)#Print stars assign based on i
for i in range(1,4):#Print upper part start from 1 to 3
    print("* "*i)#Print stars assign based on i
```

    * * * 
    * * 
    * 
    * 
    * * 
    * * * 
    


```python
y= True #or False
type(y)
```




    bool




```python
#LIST []
```


```python
mylist=[1,2,3,4,5]
type(mylist)
```




    list




```python
len(mylist)
```




    5




```python
mylist=["re","re",1,2,3,4,True,False]
len(mylist)
```




    8




```python
type(mylist)
```




    list




```python
my_list=[1,2,3,4,["elek","nyebelin"],False, True]#Nested list 
len(my_list)
```




    7




```python
my_list=["one","two","three","four"]
my_list[0]
```




    'one'




```python
my_list[2]
```




    'three'




```python
my_list[3]
```




    'four'




```python
my_list[-1]
```




    'four'




```python
#SLICING
```


```python
my_list[1:]#Start :end
```




    ['two', 'three', 'four']




```python
my_list[3:]
```




    ['four']




```python
my_list[1:2]
```




    ['two']




```python
my_list[0:3]
```




    ['one', 'two', 'three']




```python
mylist=[0,1,2,3,4,5,6,7,8,9,10]
mylist[2:4]
```




    [2, 3]




```python
mylist[0:9:2]
```




    [0, 2, 4, 6, 8]




```python
mylist[0:9:3]
```




    [0, 3, 6]




```python
mylist[0:7:3]
```




    [0, 3, 6]




```python
mylist[0:9:1] #1 is the step or stride. It determines how the slicing progresses through the list.
#In this case, with a step of 1, it includes every element in the specified range
```




    [0, 1, 2, 3, 4, 5, 6, 7, 8]




```python
#STRINGS ARE IMMUTABLE CANNOT BE CHANGE
```


```python
#List are mutable 
```


```python
my_list= [1,2,3,4,5,6,7,8,9,10]#The given list from 1-10
#Adding or appending 10 value  by concatenate
my_list= my_list + [10] 
my_list #Print my_list to add the 10 value 
```




    [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 10]




```python
list1=["a","b","c"] #The given list from a to c
list2=["x","y","z"] #The given list from x to z
newlist= list1+list2 #Adding or appending both variables into a new list 
newlist #Print the newlist to mix the values 
```




    ['a', 'b', 'c', 'x', 'y', 'z']




```python
my_list 
```




    [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 10]




```python
my_list*3
```




    [1,
     2,
     3,
     4,
     5,
     6,
     7,
     8,
     9,
     10,
     10,
     1,
     2,
     3,
     4,
     5,
     6,
     7,
     8,
     9,
     10,
     10,
     1,
     2,
     3,
     4,
     5,
     6,
     7,
     8,
     9,
     10,
     10]




```python
my_list+my_list
```




    [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 10, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 10]




```python
a = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
a.append(11)
```


```python
a = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10] #The given the list 

a.append(11)#To add 11 on the list 

a

```




    [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11]




```python
a=5
a+a
```




    10




```python
a.append('UCDS')
a
```




    [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 'UCDS']




```python
a.pop()
```




    'UCDS'




```python
a
```




    [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11]




```python
a.pop(0)#To remove 0 from the list 
a
```




    [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11]




```python
a.reverse()#To reverse the list
a
```




    [11, 10, 9, 8, 7, 6, 5, 4, 3, 2, 1]




```python
b= [3,5,4,1,2] #The given list, although there are integers, I should put square bracket in the list 
b.reverse()#Add function to reverse 
b #print the new version of the list
```




    [2, 1, 4, 5, 3]




```python
b.sort() #to sort in order
b #print the list,REMEMBER
```




    [1, 2, 3, 4, 5]




```python
b.sort(reverse=True) #Another that provided by phyton 
b
```




    [5, 4, 3, 2, 1]




```python
mylist= [1,2,2,3,4,5] #The given list 
mylist.count(1) #Count the total of"1"
```




    1




```python
mylist.count(2)
```




    2




```python
mylist.count(6)
```




    0




```python
mylist
```




    [1, 2, 2, 3, 4, 5]




```python
mylist + [6,7] #to add 2 values to mylist
```




    [1, 2, 2, 3, 4, 5, 6, 7]




```python
mylist #the list will remain same 
```




    [1, 2, 2, 3, 4, 5]




```python
mylist = [1,2,3]
mylist.extend([6,7])  #to add 2 values permanently into mylist
mylist  #generate my list, REMEMBER 
```




    [1, 2, 3, 6, 7]




```python
mylist = [1,2,3]
mylist.append([6,7])  #to add one element into mylist
mylist  #generate my list, REMEMBER 
```




    [1, 2, 3, [6, 7]]




```python
APPEND and EXTEND are DIFFERENT 
```


```python
mylist = [1,2,4,5,6]#The list is given
mylist.insert(2,3)#Starting from index two and end with 3-1 =2
mylist #generate my list, REMEMBER
```




    [1, 2, 3, 4, 5, 6]




```python
mylist = [2,3,4,5,6] #Given the list
mylist.insert(0,1) #starting from index 0 and end with 1
mylist #generate my list, REMEMBER 
```




    [1, 2, 3, 4, 5, 6]




```python
mylist = [1,2,4,5,6]#The list is given
mylist.insert(6,7)#Starting from index to and end with 3-1 =2
mylist #generate my list, REMEMBER
```




    [1, 2, 4, 5, 6, 7]




```python
mylist = [1,2,4,5,6]#The list is given
mylist.insert(3,"insert")#Starting from index three and add "insert"
mylist #generate my list, REMEMBER
```




    [1, 2, 4, 'insert', 5, 6]




```python
mylist
```




    [1, 2, 4, 5, 6, 7]




```python
mylist.remove(7)
mylist
```




    [1, 2, 4, 5, 6]




```python
mylist = [1,2,4,'insert',5,6]
mylist.remove('insert')
mylist
```




    [1, 2, 4, 5, 6]




```python
list1 = [1,2,3] #Given the list in on the list 1

list2 = list1 #Assi

list1  = [18,19,20]

print(list1)
print(list2)
```

    [18, 19, 20]
    [1, 2, 3]
    


```python
mylist = [1,2,3,4,5,6] #Given the list from 1-6

if 4 in mylist: #if 4 is appeared in mylist
    print("4 is exist") #Give the proof that 4 is available 
else: #If 4 is not appeared in mylist 
    print("4 doesn't exist") #Give the proof that 4 is unavailable
```

    4 is exist
    


```python
mylist = [1,2,3,4,5,6] #Given the list from 1-6

if 7 in mylist: #if 7 is appeared in mylist
    print("7 is exist") #Give the proof that 7 is available 
else: #If 7 is not appeared in mylist 
    print("7 doesn't exist") #Give the proof that 7 is unavailable
```

    7 doesn't exist
    


```python
mylist = [1,2,3,4,5,6] #Given the list from 1-6

if mylist.count(4)==0: #to count if 4 is not in mylist
    print("4 is not exist") #Give the proof that 4 is unavailable 
else: #If 4 is appeared in mylist 
    print("4 is exist") #Give the proof that 4 is available
```

    4 is exist
    


```python
mylist = [1,2,3,4,5,6] #Given the list from 1-6
squarelist = [] #An empty list

for i in mylist: #i assign to mylist
    squarelist.append(i**2)#Adding the value of i to the power by 2 to the squarelist
print(squarelist) #Print squarelist that each value is to the power by 2
```

    [1, 4, 9, 16, 25, 36]
    


```python
# find the max element in the list (without using max function)
# find the min elelement in the list (without using min function)
# find sum of all elements of the list
# find product of all elements in the list
# find average of all elements in the list
# create a new list of all even numbers from the original list
```

###### list=[21,]

for i in range(1,6):
    print(str(i)*i)


```python
# find the max element in the list (without using max function)
mylist = [14,20,36,98,45,761,75] #Given the list 

maxnum = mylist[0] #Assign the max number with the first element of mylist

for i in mylist: #Assign "i" to "mylist"
     if i > maxnum: #if i greater than max number
            maxnum=i #the max number is equal to i
print("Max element is",maxnum) #Print the max number is 761
```

    Max element is 761
    


```python
# find the min element in the list (without using max function)
mylist = [14,20,36,98,45,761,75] #Given the list 

minnum = mylist[0]# Initialize the sum to zero

for i in mylist:# Iterate through each element in the list
     if i < minnum: #if i less than max number
            minnum=i #the min number is equal to i
print("Max element is",minnum) #Print the in number is 14
```

    Max element is 14
    


```python
# Find the sum of all elements in the list
mylist = [23, 34, 45, 67, 78, 98]  # Given the list

mysum = 0  # Initialize the sum to zero

for i in mylist:  # Iterate through each element in the list
    mysum += i  # Add the current element to the sum

print(mysum)  # Print the final summation

```

    345
    


```python
# find average of all elements in the list
mylist = [23,43,56,76,75,64] #Given the list 
total_sum = 0  #Initialize the sum to zero 

for i in mylist:#Iterate through each element in the list
    total_sum +=i  #Summation of total i to the total sum
avg_sum = total_sum/len(mylist)#divide total sum by the length of the mylist, 6 elements to get the average
print("The average is",avg_sum)#Print the average result
```

    The average is 56.166666666666664
    


```python
# find product of all elements in the list
mylist=[1,4,5,7,9,8]#Given the list
total_product= 1 #Initialize the sum to zero

for i in mylist: #Iterate through each element in the list 
    total_product*=i #Multipication of total i to the total product 
    
print("The product of all elements is:",total_product) #Print the product
```

    The product of all elements is: 10080
    


```python
# create a new list of all even numbers from the original list
mylist = [2,76,45,32,8,96] #Given the list
oddlist=[] #An odd empty list
evenlist=[] #An even  empty list 

for i in mylist:#Iterate through each element in the list
    if i%2==0: #if i is equal to the odd number
        oddlist.append(i) #add the elements of odd numbers
    else: #while if i equal to the even numbers
        evenlist.append(i) #add the elements of even number
        
print("Even numbers are", evenlist) #print the element of even  number 
print("Odd numbers are", oddlist)#print the element of odd number
```

    Even numbers are [45]
    Odd numbers are [2, 76, 32, 8, 96]
    


```python
for i in range(1,6): #Start from 1 and end with 5
    print(str(i)*i)
```

    1
    22
    333
    4444
    55555
    


```python
for i in range(0,6):#Start from 0 (blank space) and end with 5 
    print(str(i)*i)
```

    
    1
    22
    333
    4444
    55555
    


```python
Q1. 

s="21-10-2022"
Write program to print

Day = 
Month=
Year = 
```


```python
s="21-10-2022" #Given a string consist of day,month,year
day, month, year= s.split("-")
print("Day=",day)
print("Month=",month)
print("Year=",year)
```

    Day= 21
    Month= 10
    Year= 2022
    


```python
Q2. Accepts Marks, < 35 - Fail 35 - 60 - C Grade 61 - 80 - B Grade 81 - 100 - A Grade 
Check for values < 0 and > 100 as well with error messages.
```


```python
x=int(input('Enter the number:'))#Ask the user to enter the number

if x<0 or x>100: #if x is less than 0 or greater than 100
    print("Error") #Give the outcome that is error 
elif x<= 35: #if x is less or equal to 35 
    print("Fail") #Give the outcome that is fail
elif x>35 and x<=60:#if x is greater than 35 and x is less or equal to 60
    print("C Grade") #Give the outcome is C Grade
elif x>61 and x<=80:#if  x is greater than 61 and x is less or equal to 80
    print("B Grade")#Give the outcome is B Grade
else: #If x is greater than 81 and less or equal to 100
    print("A Grade")#Give the outcome is A grade 
```

    Enter the number:97
    A Grade
    


```python
Q3. Write a code to print all the values from 1 to 100. Skip the number which are divisible by 3 or 5
```


```python
for x in range(1, 101): #to write a row starting from 1 to 100
    if x % 3 == 0 or x%5==0: #if the value of is divisble by 3 or 5
        continue  # Skip this iteration if x is divisible by 3 or 5
    print(x)#generate 1 to 100 without the number divisble by 3 or 5
```

    1
    2
    4
    7
    8
    11
    13
    14
    16
    17
    19
    22
    23
    26
    28
    29
    31
    32
    34
    37
    38
    41
    43
    44
    46
    47
    49
    52
    53
    56
    58
    59
    61
    62
    64
    67
    68
    71
    73
    74
    76
    77
    79
    82
    83
    86
    88
    89
    91
    92
    94
    97
    98
    


```python
for x in range(1, 101): #to write a row starting from 1 to 100
    if x % 3 == 0 or x%5==0: #if the value of is divisble by 3 or 5
        continue  # Skip this iteration if x is divisible by 3 or  5
    print(x)#generate 1 to 100 without the numbers divisble by 3 or 5
```

    1
    2
    4
    7
    8
    11
    13
    14
    16
    17
    19
    22
    23
    26
    28
    29
    31
    32
    34
    37
    38
    41
    43
    44
    46
    47
    49
    52
    53
    56
    58
    59
    61
    62
    64
    67
    68
    71
    73
    74
    76
    77
    79
    82
    83
    86
    88
    89
    91
    92
    94
    97
    98
    


```python
Q4. Check in an element exists in a list
```


```python
a_list =[1,2,3,4,5,6,7,8,9] #Given the list 

if 10 in a_list: #if there is 10 in a_list
    print("That is in here") #Give a proof there is 10
else: #If 10 it's not in a_list
    print("That's not in the list") #Give a proof there is no 10
```

    That's not in the list
    


```python
mylist = [1,2,3,4,5,6] #Given the list from 1-6

if mylist.count(5)==0: #to count if 5 is not in mylist
    print("5 is not exist") #Give the proof that 5 is unavailable 
else: #If 5 is appeared in mylist 
    print("5 is exist") #Give the proof that 5 is available
```

    5 is exist
    


```python
mylist = [1,2,3,4,5,6] #Given the list from 1-6
element=int(input("Enter the number:"))

if element in mylist: #to count if the number is not in mylist
    print("This is exist") #Give the proof that the number is unavailable 
else: #If the number is appeared in mylist 
    print("This is not exist") #Give the proof that the number is  available
```

    Enter the number:4
    This is exist
    


```python
#METHOD 1
found = False  # Initialize a boolean variable to keep track of whether the element is found

for i in mylist:#Iterate through each element in the list
    if i == 5:#if 5 is exist in i 
        print("The element exists") #Give a proof that is exist
        found = True  # Set 'found' to True when the element is found

if not found: #if it is not exist
    print("The element does not exist")  # If 'found' is still False, the element was not found
```

    The element exists
    


```python
mylist = [1, 2, 3, 4, 7, 8] #Given the list

if "5" in mylist: #if 5 is exist in mylist
    print("It exists")#Give a proof that 5 is exist
else: #otherwise, if 5 is not exis 
    print("It does not exist") #Give a proof that 5 is not exist
```

    It does not exist
    


```python
# Method 3:
if mylist.count(5) > 0: #Count the element of 5 if it is exis
    print("It exists") #Give a proof that 5 is exist
else:#Otherwise 
    print("It does not exist") #Give a proof that 5 is not exist

```

    It does not exist
    


```python
s = "abcdef" #Given the list from a-f
for c in s:#Iterate through each element in the list
    print(c) #Generate c into a row 
```

    a
    b
    c
    d
    e
    f
    


```python
# Accessing characters at even positions in a string

s = "abcdef"

# Using a for loop to iterate through indices in the string
# The range function starts at 0, goes up to the length of the string 's' with a step of 2
# This means it accesses characters at even positions

for i in range(0, len(s), 2):
    print(s[i])  # Print the character at index 'i' in the string 's'

```

    a
    c
    e
    


```python
#LIST RELATED 
mylist = [1,2,5,7,9,4]
for i in mylist:#Iterate through each element in the list
    if i %2==0:
        print(i)
```

    2
    4
    


```python
mylist = [1,2,5,7,9,4] #Given the list
sqlist=[] #Empty square list

for i in mylist:#Iterate through each element in the list
    sqlist.append(i**2) #convert teh elements to the power 2
print(sqlist) #Print the power by 2 numbers
```

    [1, 4, 25, 49, 81, 16]
    


```python
# Given the list 'mylist' containing lowercase letters

mylist = ["a", "b", "c", "d"]

# Initialize empty lists to store the results
uplist = []  # Empty list for uppercase versions of elements
asclist = []  # Empty list for ASCII values of elements

# Iterate through each element in the list 'mylist'
for i in mylist:
    # Convert the element to uppercase and append it to 'uplist'
    uplist.append(i.upper())

    # Get the ASCII value of the element and append it to 'asclist'
    asclist.append(ord(i))

# Print the list of uppercase elements
print(uplist)

# Print the list of ASCII values
print(asclist)
```

    ['A', 'B', 'C', 'D']
    [97, 98, 99, 100]
    


```python
1. Iniatialize one empty list
2. For loop to iterate over each element
3. use append along with the expression (upper, ord, i%2)
4. print
```


```python
# List Comprehension (efficient, optimized) in creating a new list from existing list
```


```python
mylist = [1,2,5,7,9,4]
sqlist = []
for i in mylist:
    sqlist.append(i**2)
print(sqlist)
```

    [1, 4, 25, 49, 81, 16]
    


```python
mylist = [1,2,5,7,9,4] #Given the list
sqlist = [i**2 for i in mylist] #Make the list to the power by 2
print(sqlist)  #Print square list
```

    [1, 4, 25, 49, 81, 16]
    


```python
mylist = ["a", "b", "c", "d"] #Given list of strings 
uplist = [i.upper() for i in mylist] #Make the list to the power by 2
asclist =[ord(i)for i in mylist] # Create a new list 'asclist' with ASCII values of the elements

print(uplist)# Print the list 'uplist' containing uppercase versions of the elements
print(asclist)# Print the list 'asclist' containing ASCII values of the elements
```

    ['A', 'B', 'C', 'D']
    [97, 98, 99, 100]
    


```python
[Expression for name in list]
```


```python
celsius = [0,10,1,34.5] #Given the list in celsius
fh = [9/5*i +32 for i in celsius]#Convert celsius into i and calculate from celcius to fahrenheit
print(fh)#Print the list in degree Fahrenheit
```

    [32.0, 50.0, 33.8, 94.1]
    


```python
mylist = [1,2,5,7,9,4] #Given the list
evenlist = [i for i in mylist if i%2==0 ]#If some elements are divisible by 2 /even numbers

print(evenlist)#Print just for even numbers 
```

    [2, 4]
    


```python
mylist = [-1,2,-6,0,9,5] #Given the list
poslist = [i for i in mylist if i>0] #Just give the positive numbers using list comprehension

print(poslist) #print positive numbers 
```

    [2, 9, 5]
    


```python
# Given a list of integers 'mylist' representing ASCII values

mylist = [65, 66, 67, 68]

# Create a new list 'charlist' with corresponding characters using list comprehension
charlist = [chr(i) for i in mylist]

# Print the 'charlist' containing characters corresponding to the ASCII values
print(charlist)
```

    ['A', 'B', 'C', 'D']
    


```python
# Given a list of strings 'mylist'

mylist = ["hello", "world", "of", "programming"]

# Create a new list 'flist' with the first character of each string using list comprehension
flist = [i[0] for i in mylist]

# Print the 'flist' containing the first characters of the strings
print(flist)
```

    ['h', 'w', 'o', 'p']
    


```python
# Given a list of strings 'mylist'
mylist = ["hello", "world", "of", "programming"]

# Create an empty list 'flist' to store the first characters
flist = []

# Iterate through each string in 'mylist' using a single loop
for i in mylist:
    flist.append(i[0])  # Extract the first character of each string and add it to 'flist'

# Print the 'flist' containing the first characters of the strings
print(flist)
```

    ['h', 'w', 'o', 'p']
    


```python
num = 347
revnum = 743
```


```python
347

3 hundred forty seven

3*100 + 4*10 + 7*1

3 4 7

7*100 + 4*10 + 3*1 = 743
```


```python
347

347 -> 7 

347 % 10 =  7 units

347 - > 34 347//10 = 34

34  % 10 =  4
...
...
3

7 4 3 
```


```python
num = 347 #output should be 347
a = 347//100 #variable a, 347 divide by 100 rounded off to 3
b =47//10 #variable b, 47 divide by 10 rounded of to 4
c=7%10 #variable c 10 divide by 7 gives a remainder 3
print(c,b,a) #print 3 reversed variables 
```

    7 4 3
x = [1900, 1990, 2004, 2012, 2017]

for year in x:
    if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
        print(str(year) + " is a leap year")
    else:
        print(str(year) + " is not a leap year")

#List Comprehension 
x = [1900, 1990, 2004, 2012, 2017]

leap_years = [str(year) + " is a leap year" if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0) else str(year) + " is not a leap year"]

for result in leap_years:
    print(result)


    
