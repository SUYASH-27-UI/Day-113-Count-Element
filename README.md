# Day-113-Count-Element
# Python Day 113 - Count an Element

This program counts how many times a particular element appears in a Python list using the `count()` method.

## Example

List:

```text id="7v4q0a"
[10, 20, 30, 20, 40, 20, 50]
```

Element:

```text id="1r9n6w"
20
```

Output:

```text id="h3k8vp"
20 appears 3 times.
```

## Concepts Used

* List
* `count()` method
* Variables
* Counting elements
* `print()`

## How It Works

1. A list of numbers is created.
2. The number to count is stored in a variable.
3. The `count()` method searches the list for that number.
4. It counts how many times the number appears.
5. The result is stored in the `count` variable.
6. The total count is displayed.

## Python Code

```python id="u7p3nc"
numbers = [10, 20, 30, 20, 40, 20, 50]

print("List:", numbers)

number = 20

count = numbers.count(number)

print(number, "appears", count, "times.")
```

## Output

```text id="2s8v1k"
List: [10, 20, 30, 20, 40, 20, 50]
20 appears 3 times.
```

## Goal

The goal of this project is to understand the `count()` method and learn how to count the occurrences of an element in a Python list.
