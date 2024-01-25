# Functions with Returns

## JavaScript

```javascript
function sayHello(person){
    return `Hello ${person}`
}

let message = sayHello("Bruce")
console.log(message)
```

## Python

```python
def sayHello(person):
    return f"Hello {person}"

message = sayHello("Bruce")
print(message)
```

## PHP

```php
function sayHello($person){
    return "Hello! $person";
}

$message = sayHello("Bruce");
echo $message;
```

## C\#

``` C#
// Stand alone functions don't exist in C#. All behavior belongs to a class. "Functions" that are part of a class are called methods.
// first we must define a class and its methods
public class SomeClass
{
    public static string StaticSayHello(string personName)
    {
        // The $ is equivalent to an f string in Python. In C# it's called interpolation.
        return $"Hello {personName}"; 
    }

    public string NonStaticSayHello(string personName)
    {
        return $"Hello {personName}";
    }
}
// Note that the methods define a return type of string. 

// A static method is the closest thing to a stand along function. It is called as follows using the class name and method name. with a dot between them.
Console.WriteLine( SomeClass.StaticSayHello("Bruce") );

// To invoke a non-static or regular method you must first instantiate (create) an object, then use the object name and method name to call the method. Note that the class name is the type of the object variable and the new operator is used to create the object in memory.
SomeClass classObject = new SomeClass();
Console.WriteLine( classObject.NonStaticSayHello("Bruce") );
```
