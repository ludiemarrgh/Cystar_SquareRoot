# How to Find Square Root 

The square root of a number is the factor that we can multiply by itself to get that number, there are 3 ways to find square root

## 1.Using Exponent(Square_Root.py)


```
number = float(input("enter a number: "))
sqrt = number ** 0.5
print("square root:", sqrt)
```
In above program, first we’re taking a number from user as input and the entered value will be converted to int from string and will store into variable called number. Then we are using  exponent sign which are two asterisks signs, which is used to find out the power of a number. But we know that if a number have power ½ or 0.5 then it will represent to the square root of that number. That’s why we are using 0.5 as power here. So the number**0.5 will give us square root of that number and will be stored in variable named as sqrt. In last line we’re just printing the square root of the number.


## 2.Using math.sqrt (Square_Root2.py)

```
import math
number = float(input("enter a number:"))
sqrt = math.sqrt(number)
print("square root:" , sqrt)
```
sqrt() is the predefined method used to find square root in python. But we have to import math module to use the sqrt() method. In first line, we’re importing math module, then in next line, taking input from user. After that we’re finding the square root of the number using sqrt() method and result will be stored into sqrt variable. In last line, just printing the square root as in first program.

## 3.Using math.pow(Square_Root3.py) 

```
import math
number = float(input("enter a number:"))
sqrt = math.pow(number, 0.5)
print("square root: ", sqrt)
```
pow() is also a predefined method to find out power of a number, it takes two arguments as input, first is the number itself and second one is power of that number. The program is same as first program where we’re using (**) sign to find out the square root but only different is this that here we’re using a predefined method pow() instead of the two asterisks signs to get the power of that number.

## Links
[The crazy programmer](https://www.thecrazyprogrammer.com/2018/05/how-to-find-square-root-in-python.html) | [Cue math](https://www.cuemath.com/algebra/squares-and-square-roots/) | [Khan Academy](https://www.khanacademy.org/math/cc-eighth-grade-math/cc-8th-numbers-operations/cc-8th-roots/a/square-roots-review#:~:text=The%20square%20root%20of%20a,opposite%20of%20squaring%20a%20number.)
