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