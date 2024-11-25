# javalearning
## _Variables_
- [x] [Variables](#variables-explanation)
- [x] [List](#arrays-explanation)
- [x] [Arrays](#arrays-explanation)
- [x] [Data Types](#data-types-explanation)
- [x] [Operators](#operators-explanation)
      
## _Selection_
- [ ] [If and If else statements](#if-and-if-else-statements)
- [ ] [Switch Statements](#switch-statements)
- [ ] [Functions](#functions)

## _Iteration_
- [ ] [While Statements](#while-statements)
- [ ] [For Statements](#for-statements)
- [ ] [Break and Continue](#break-and-continue)

## _Methods_
- [ ] [Methods](#methods)
- [ ] [Method Perameter](#method-perameter)
- [ ] [Switch Statements](#switch-statement)



### Variables Explanation
Java has the same data types as lots of the other ones:
- string
- int
- float
- char
- bool
they are assigned through saying the data type and then the name. for example:
```java
int myNum = 5;             
float myFloatNum = 5.99f;
char myLetter = 'D';
boolean myBool = true; 
String myText = "Hello"; 
```
### Arrays Explanation
java does not have a built in list or array functionality. therefore you have to import it
```java
import java.util.ArrayList;
ArrayList<String> cars = new ArrayList<String>();
```
to make an array, you have to specify the data type which the array would be in <>.

When adding things to a list, you have to use the .add function to the list
```java
ArrayList<String> cars = new ArrayList<String>();
cars.add("Volvo");
cars.add("BMW");
cars.add("Ford");
cars.add("Mazda");
System.out.println(cars);
```
To print out the list you use the normal println function and just the name of the array or list.
### Data Types Explanation

| Data Type | Size    | Description    |
| :---:   | :---: | :---: |
| byte | 1 byte   | 	Stores whole numbers from -128 to 127   |
| short | 2 bytes  | Stores whole numbers from -32,768 to 32,767   |
| int | 4 bytes   | Stores whole numbers from -2,147,483,648 to 2,147,483,647   |
| long | 8 bytes   | 	Stores whole numbers from -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807   |
| float | 4 bytes   | 	Stores fractional numbers. Sufficient for storing 6 to 7 decimal digits   |
| double | 8 bytes   | 	Stores fractional numbers. Sufficient for storing 15 to 16 decimal digits   |
| boolean | 1 byte   | 	Stores true or false values   |
| char | 2 bytes   | 	Stores a single character/letter or ASCII values |

data types are in two groups:

 - Primitive data types - includes byte, short, int, long, float, double, boolean and char
 - Non-primitive data types - such as String, Arrays and Classes (you will learn more about these in a later chapter)
### Operators Explanation
operaters in java are the same as in other langs. there are
```
+ addition
- subtraction
= equals
* multiplication
/ division
There is no operator for integer divide, instead the result variable must be an int as it would cut off the decimal
% modulus 
++ incriment by 1
-- decrement by 1
```


### If and If else statements
When it comes to if else statements, operaters are used to determine certain things.
It works like in other languages.
Unlike python, there are no elif statements, instead it is a else if statement such in C.
Else is being used in the way where if something is not the value you originally tested, you can use it.

*Short hand if else:*
```java
variable = (condition) ? expressionTrue :  expressionFalse;
```
In short hand if else, you can reduce errors by having one line if statments.
The value before the `?` is often an expression which equates to true or false. This is when the expression before determines whether the value with the ? is assigned to the variable, or the value after the : which is if it is false.

### Switch Statements
### Functions

### While Statements
### For Statements
### Break and Continue

### Methods
### Method Perameter
### Switch Statements


