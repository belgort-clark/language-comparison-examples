# Functions with No Arguments

## JavaScript

```javascript
function sayHello(){
    console.log("Hello!")
}

sayHello()
```

## Python

```python
def sayHello():
    print("Hello!")

sayHello()
```

## PHP

```php
function sayHello(){
    console.log("Hello!");
}

sayHello()
```

## C\#

``` C#
// Stand alone functions don't exist in C#. All behavior belongs to a class. "Functions" that are part of a class are called methods.
// first we must define a class and its methods
public class SomeClass
{
    public static void StaticMethod()
    {
        Console.WriteLine("Hello!");
    }

    public void NonStaticMethod()
    {
        Console.WriteLine("Hello!");
    }
}
// Note that the methods define a return type of void. This implies that nothing is returned.

// A static method is the closest thing to a stand along function. It is called as follows using the class name and method name. with a dot between them.
SomeClass.StaticMethod();

// To invoke a non-static or regular method you must first instantiate (create) an object, then use the object name and method name to call the method. Note that the class name is the type of the object variable and the new operator is used to create the object in memory.
SomeClass classObject = new SomeClass();
classObject.NonStaticMethod();

```
