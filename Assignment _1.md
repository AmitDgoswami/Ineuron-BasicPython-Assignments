1. In the below elements which of them are values or an expression? eg:- values can be
integer or string and expressions will be mathematical operators.

*
'hello'
-87.8
-
/
+
6

Ans: There are a total of 4 Operators and 3 Expressions,
They are:
         Operators: *,-,/,+
         Expressions: 'hello', 87.8, 6

2. What is the difference between string and variable?
Ans: STRING:- A String is a group of characters or a single character usually enclosed in Double quotes " " or single quotes ' '. Even triple quotes can be used in Python but generally used to represent multiline strings and docstrings. Eg: my_string = 'Hello'

VARIABLE:- A Variable is used to store of information, and a String is a type of information you would store in a Variable. A variable is created the moment you first assign a value to it. Example: x = 5, y = "Amit". Here x and y are variables.

3. Describe three different Data Types ?
Ans: Three fundamental Data types in python are int, float, complex.

int data type: We can use int data type to represent whole numbers. Eg: int_num=10
float data type: We can use float data type to represent floating point values. Eg: flo_num=2.5
complex data type: Complex number is represented by complex class. Eg: com_num=15+2.5j


```python
# Example for int data type
int_num=10
print(int_num, type(int_num))
# Example for float data type
flo_num=2.5
print(flo_num, type(flo_num))
# Example for Complex data type
com_num=15+2.5j
print(com_num, type(com_num))
```

    10 <class 'int'>
    2.5 <class 'float'>
    (15+2.5j) <class 'complex'>
    

4. What is an expression made up of? What do all expressions do?
Ans: An expression is a combination of values, variables, operators, and calls to functions. Expressions need to be evaluated. If we ask Python to print an expression, the interpreter evaluates the expression and displays the result. An expression is evaluated as per the precedence of its operators. So that if there is more than one operator in an expression, their precedence decides which operation will be performed first.


```python
 # Eg of Expressions
    
20-10+15*3    
    
```




    55



5.This assignment statements, like spam = 10. What is the difference between an expression and a statement?

Ans: An expression is a combination of values, variables, and operators.When we type an expression at the prompt, the interpreter evaluates it, which means that it finds the value of the expression.An expression is evaluated as per the precedence of its operators. So that if there is more than one operator in an expression, their precedence decides which operation will be performed first.

eg: 20-10+15*3 is an example of a expression

A statement is a unit of code that has an effect, like creating a variable or displaying a value.When we type a statement, the interpreter executes it, which means that it does whatever the statement says. In general, statements don’t have values. A statement is an instruction that a Python interpreter can execute. There are mainly four types of statements in Python, Print statements, Assignment statements, Conditional statements and Looping statements.

eg: CourseName = 'I am going to be a data scientist', spam = 10


```python
#Eg:
20-10+15*3 # Is a Expression
courseName = 'I am going to be a data scientist by next year' # Is a Statement
print("iNeuron") # Is a Expression Statement
```

    iNeuron
    

6.After running the following code, what does the variable bacon contain?
bacon = 22
bacon + 1

Ans: The variable bacon is set to 22 .The expression bacon + 1 does not reassign the value in bacon (that would the case if the expression is like bacon = bacon + 1 instead of bacon + 1)


```python
# Eg Case#1
bacon=22
bacon + 1
print(bacon)
```

    22
    


```python
#Eg Case#2
bacon=22
bacon=bacon+1 
print(bacon)
```

    23
    

7.What should the values of the following two terms be?
'spam'+'spamspam'
'spam'*3

Ans: Both expressions evaluate to the string 'spamspamspam' Where as the first expression follows String Concatentation and the second expression follows String Multiplication


```python
print('spam'+'spamspam') # str concatenation
print('spam'*3) # str multiplication
```

    spamspamspam
    spamspamspam
    

8. Why is eggs a valid variable name while 100 is invalid?
Ans: As per python,Variable names cannot begin with a number. The python rules for naming a variable are :-

1.Variable name must start with a letter or the underscore character.
2.Variable name cannot start with a number.
3.Variable name can only contain alpha-numeric characters and underscores.
4.Variable names are case-sensitive.
5.The reserved words cannot be used naming the variable.


```python
egg='Amit' # Valid variable Initilization
100='ineuron' # Invalid Variable Initilization
print(egg) #prints the value of egg ie Ineuron
print(100) # Raises a Syntax Error as 100 is not a valid variable name
```


      File "C:\Users\DELL\AppData\Local\Temp/ipykernel_10116/618000139.py", line 2
        100='ineuron' # Invalid Variable Initilization
        ^
    SyntaxError: cannot assign to literal
    


9.What three functions can be used to get the integer,floating-point number,or string version of a value?

Ans: The int(),float(),and str() functions will evaluate to the integer,floating-point number,string version of the value passed to them.


```python
# Eg:
print('int(10.0) -> ',int(10.0)) 
print('float(10) -> ',float(10)) 
print('str(10) -> ',str(10)) 
```

    int(10.0) ->  10
    float(10) ->  10.0
    str(10) ->  10
    

0.Why does this expression cause an error? how can you fix it?
'I have eaten ' + 99 + 'burritos.'

Ans: This cause of error because 99 is not a string. 99 must be typecasted to a string to fix this error. The correct way of representing is mentioned below:
Input: 'I have eaten ' + str(99) + 'burritos.'
Output: 'I have eaten 99 burritos.'


```python
print('I have eaten '+str(99)+' burritos')
```

    I have eaten 99 burritos
    


```python

```
