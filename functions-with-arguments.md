# Functions with Arguments

## JavaScript

```javascript
function sayHello(person){
    console.log(`Hello ${person}`)
}

sayHello("Bruce")
```

## Python

```python
def sayHello(person):
    print(f"Hello {person}")

sayHello("Bruce")
```

## PHP

```php
function sayHello($person){
    console.log("Hello! $person");
}

sayHello("Bruce");
```

## C\#

``` C#
// Stand alone functions don't exist in C#. All behavior belongs to a class. "Functions" that are part of a class are called methods.
// first we must define a class and its methods
public class SomeClass
{
    public static void StaticMethod(string personName)
    {
        // The $ is equivalent to an f string in Python. In C# it's called interpolation.
        Console.WriteLine($"{personName}"); 
    }

    public void NonStaticMethod(string personName)
    {
        Console.WriteLine($"{personName}");
    }
}
// Note that the methods define a return type of void. This implies that nothing is returned.

// A static method is the closest thing to a stand along function. It is called as follows using the class name and method name. with a dot between them.
SomeClass.StaticMethod("Bruce");

// To invoke a non-static or regular method you must first instantiate (create) an object, then use the object name and method name to call the method. Note that the class name is the type of the object variable and the new operator is used to create the object in memory.
SomeClass classObject = new SomeClass();
classObject.NonStaticMethod("Bruce");

```
