# JP-Python-101
python notes  

1. [Expressions](#expressions)
2. [Data Type](#data-type)








## Expressions

### Basic Operators
```python
a=b                     #declare value of a to be b
+a                      #unary positive, does nothing
a+b                     #sum or connect strings
-a                      #unary negative, return negative a
a-b                     #subtract
a*b                     #multiply
a**b                    #exponent, a to the power of b
a/b                     #divide
a%b                     #modulo, return remainder of a/b
```
### Bitwise Operators(not tested at all i think)
```python
<<                      #left binary shift
>>                      #right binary shift
&                       #bitwise AND
|                       #bitwise OR
^                       #bitwise XOR
~                       #bitwise invert
```
### Assignment Operators:
you can add a "=" with above operators to include assignment  
e.g.
```python
a+=b                    #a=a+b
a**=b                   #a=a**b
a<<=b                   #a=a<<b
```
### Boolean Operators
return 1 or ```True``` if is correct
```python
a<b                     #less than
a>b                     #greater than
a<=b                    #less than or equal to
a>=b                    #greater than or equal to
a==b                    #equal to
a!=b                    #not equal to
```
### Logic Operators
```python
a and b                 #return True only when both a and b is True
a or b                  #return True as long as a or b is True
not a                   #return opposite of a
```

## Data Types

### Literals
There is a type casting funciton for each corresponding data types below  
use ```type()``` function to see each of their data type
```python
21                      #integer/decimal        
0b10101                 #binary, prefixed with "0b"
0o350                   #octal, prefixed with "0o"
0x12b                   #hexadecimal, prefixed with "0x"
10e-12                  #exponent constant 10**-12
3.0                     #float
5+6j                    #complex number 5+6i in math
True                    #boolean value 1
False                   #boolean value 0
None                    #null
'b'                     #characters
'buy'                   #strings
'''this is a doc string
it will save with this exact format when assign to variable
but can also be use as a multi line comments like this
warning indention still matter if is in functions
'''
#for string '' and "" doesn't really matters
[1,2,3]                 #list,ordered, changeable and allow duplicate values
(6,7,8)                 #tuple,ordered and unchangeable and allow duplicate values
{9,10,11}               #set,unordered, unchangeable and do not allow duplicate values
{key:value,'hi':14}     #dictionary, ordered, changeable and do not allow duplicates
```
### Escape Sequences
```python
"\’"	                #Single quote
"\\’"	                #Double quote
"\\"	                #Backslash
"\n"	                #Newline
"\r"	                #Carriage Return
"\t"	                #Horizontal Tab
"\b"	                #Backspace
"\f"	                #Formfeed
"\v"	                #Vertical Tab
"\0"	                #Null Character
"\N{Name}"	            #Unicode character Database named lookup
"\uxxxxxxxx"	        #Unicode character with a 16-bit hex value
"\Uxxxxxxxx"	        #Unicode character with a 32-bit hex value
"\000"	                #Character with octal value ooo
"\xhh"	                #Character with hex value hh
```
### Type casting

