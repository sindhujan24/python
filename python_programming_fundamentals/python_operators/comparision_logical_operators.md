#Comparison Operator
Comparison operators are used to compare one value to another. The result of a comparison is a Boolean value, which can be either True or False.

1. Equal to (==) Operator
Equal to (==) operator checks whether the value of the operands are equal. If yes it returns True.

2==2
True
x = 7
y = 6
x==y
False
2. Not Equal to (!=) Operator
Not equal to (!=) operator checks If the values of the two operands are not equal, then the condition becomes true.

4!=7
True
x = 8
y = 8
x!=y
False
3. Greater than (>) Operator
Greater than (>) operator checks If the value of the left operand is greater than the value of the right operand, then the condition becomes true.

5>9
False
x = 34
y = 12
x>y
True
4. Less than (<) Operator
Less than (<) operator checks If the value of the left operand is less than the value of the right operand, then the condition becomes true.

6<10
True
x = 87
y = 10
x<y
False
5. Greater than equal to (>=) Operator
Greater than equal to (>=) operator checks If the value of the left operand is greater than or equal to the value of the right operand, then the condition becomes true.

4>=5
False
x = 76
y = 36
x>=y
True
6. Less than equal to (<=) Operator
Less than equal to (<=) operator checks If the value of the left operand is less than or equal to the value of the right operand, then the condition becomes true.

12<=13
True
x = 87
y = 76
x<=y
False
Logical Operator
Logical operators are used to combine conditional statements.

1. AND Operator
And operator Returns True if both statements are true.

x = 6
x<10 and x>1
True
2. OR Operator
OR operator Returns True if one of the statements is true.

x = 8
x<10 or x>12
True
3. NOT Operator
NOT operator Reverse the logical state of the operand.

a = True
not a
False
Bitwise Operator
Bitwise operators are used to compare (binary) numbers.

1. Bitwise AND (&) Operator
Bitwise and Operator Sets each bit to 1 if both bits are 1.

# 10 = 1010
# 11 = 1011
10&11
10
2. Bitwise OR ( | ) Operator
Bitwise or operator Sets each bit to 1 if one of two bits is 1.

10|12
14
3. Bitwise NOT (~) Operator
Bitwise not operator Inverts all the bits.

~11
-12
4. Bitwise Left Shift Operator ( << ) Operator
Bitwise left shift operator move the left operand’s value to the left by the number of bits specified by the right operand.

12<<2
48
5. Bitwise Right Shift Operator ( >> ) Operator
Bitwise right shift operator move the left operand’s value to the right by the number of bits specified by the right operand.

10>>3
1
Ninja Trap!!!
10 and 7
7
a = 10 #1010
b = 7 #0111
a&b
2
