# Creating Arrays

## JavaScript

```javascript
    // create empty array
    const grades = []
    grades.push(99) // push 1 element into the array
    grades.push(100,200,300) // push multiple elements into an array
    let lastGrade = grades.pop() // remove last element from array an store in lastGrade variable

    // Create a new array with string elements
    const students = ["Bruce","Sam","Julie","Tom"]
```

## Python

```python
    # create empty array
    grades = []
    grades.append(99) # append 1 element into the array
    grades.extend([100,200,300]) # add multiple elements into an array
    lastGrade = grades.pop() # remove last element from array an store in lastGrade variable

    # Create a new array with string elements
    students = ["Bruce","Sam","Julie","Tom"]
```

## PHP

```php
    # create empty array
    $grades = []
    array_push($grades, 99); # push 1 element into the array
    array_push($grades,[100,200,300]); # add multiple elements into an array
    $lastGrade = array_pop($grades) # remove last element from array an store in lastGrade variable

    # Create a new array with string elements
    $students = ["Bruce","Sam","Julie","Tom"];
```

## C\#

``` C#
// create an array
int[] anArrayOfInts = new int[5];
// arrays in C# are fixed in size and can't be dynamically resized. The size is specified when the array is created.

// An equivalent dynamically resizable object is the generic list
// create an empty list
List<int> arrayOfInts = new List<int>();
// note that the type of the List is defined with the type specified between the angle brackets

arrayOfInts.Add(99); // append the value of 99 onto the end of the list
int numberOfElements = arrayOfInts.Count; // returns the number of elements in the list

int[] grades = { 100, 99, 90, 100, 65 };
arrayOfInts.AddRange(grades); // adds the elements from an existing collection to the list
arrayOfInts.RemoveAt(arrayOfInts.Count - 1); // remove last element from list

// create a list from an existing array by passing the existing collection to the List constructor
string[] studentNames = { "Bruce", "Sam", "Julie", "Tom" };
List<string> students = new List<string>(studentNames);

// create a list using initialization syntax
List<string> students2 = new List<string> { "Bruce", "Sam", "Julie", "Tom" };
```
