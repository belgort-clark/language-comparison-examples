# Variable Assignment

## JavaScript

```JavaScript
let a = 42 // define the variable a with a value of 42
let b = "Bruce Elgort" // define the variable b with a value of "Bruce Elgort"
const message = "Thank You" // define the constant variable message with a value of "Thank You"
let flag = true // define the variable flag with the Boolean value of true
const grades = [100,99,90,100,65] // define the array grades with 5 numeric values
const student = {id: 1,fullName: "Bruce Elgort", gpa: 2.7} // define the object student with three key/value pairs
```

## Python

```python
a = 42 # define the variable a with a value of 42
b = "Bruce Elgort" # define the variable b with a value of "Bruce Elgort"
MESSAGE = "Thank You" # define the variable message with a value of "Thank You". Note that Python does not have the buil-in type of constant. Make the variable name all uppercase.
flag = True // define the variable flag with the Boolean value of True
grades = [100,99,90,100,65] # define the list grades with 5 numeric values
student = {"id": 1,"fullName": "Bruce Elgort", "gpa": 2.7} # define the dictionary student with three key/value pairs
```

## PHP

```php
$a = 42; // define the variable a with a value of 42
$b = "Bruce Elgort"; // define the variable b with a value of "Bruce Elgort"
define('MESSAGE') = "Thank You"; // define the constant variable message with a value of "Thank You"
$flag = true; // define the variable flag with the Boolean value of true
grades = [100,99,90,100,65]; // define the array grades with 5 numeric values
student = {"id" => 1,"fullName" => "Bruce Elgort", "gpa" => 2.7}; // define the associative array student with three key/value pairs
```

## C\#

``` C#
// C# is statically typed - all variable definitions must be preceded with a type keyword. The type can be primitives link int or double defined in the C# language or any class name.
// All statements are terminated with a semicolon - ';'
int a = 42; // define the variable a with a value of 42.
string b = "Bruce Elgort"; // define the variable b with a value of "Bruce Elgort".
const string MESSAGE = "Thank You"; //define the constant MESSAGE with a value of "Thank You". MESSAGE is not a variable and its value can't be changed. By convention constants are ALL CAPS.
bool flag = true; // define the variable flag with the Boolean value of true.
int[] someArray = new int[5]; // define an array of int with 5 elements. The new operator creates the array. Initial values are assigned separately.
int[] grades = { 100, 99, 90, 100, 65 }; // define the array of int values with a variable name of grades initialized with 5 numeric values.
Dictionary<string, string> student = new Dictionary<string, string>()
{
    {"id", "1" },
    {"fullName", "Bruce Elgort" },
    {"gpa", "2.7" }
};
// define the dictionary student with three key/value pairs. Note that the all keys have to be of the type defined for keys and all values have to be of the same type defined for the values. In this case "Numeric" values are represented as strings and must be converted to a numeric type if the programmer needs to perform numeric operations on the value.
```
