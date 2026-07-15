# 🐍 Python Basics - Beginner Friendly Notes

> Quick revision + interview notes.

## Run Python

``` bash
python --version
python app.py
python
```

Exit: - `exit()` - `Ctrl+Z + Enter` (Windows) - `Ctrl+D` (Linux/Mac)

## Comments

``` python
# Single line comment

'''Multi line comment'''
```

## Variables

``` python
name = "python basics"
numAge = 9999
isTodayThursday = True

listOfPeople = ["satya","akash","sheetal","prashant","oves","ssk"]

setOfEvenNumbers = {2,4,6,8,10}

tupleOfDays = (
    "sunday","monday","tuesday",
    "wednesday","thursday","friday","saturday"
)

dictOfBooks = {
    "book1":"art of war",
    "book2":"how to talk to psychopaths"
}
```

## print()

``` python
print("Hello World")

topic = "Python Basics"
print("We are learning", topic)
```

## input()

``` python
name = input("What is your name?")
```

## type()

``` python
print(type(name))
```

Outputs:

``` python
<class 'str'>
<class 'int'>
<class 'bool'>
<class 'list'>
<class 'tuple'>
<class 'set'>
<class 'dict'>
```

## List

-   \[\]
-   Mutable
-   Ordered
-   Allows duplicates

``` python
numbers=[9,2,8,1]
numbers.append(10)
numbers.insert(1,100)
numbers.remove(8)
numbers.sort()

print(min(numbers))
print(max(numbers))
print(sum(numbers))
```

## Tuple

-   ()
-   Immutable

``` python
days=("monday","tuesday","tuesday")
print(days.count("tuesday"))
print(days.index("tuesday"))
```

## Set

``` python
nums={1,2,2,3}
nums.add(4)
nums.remove(2)
```

## Dictionary

``` python
books={
 "book1":"Art of War",
 "book2":"Atomic Habits"
}

print(books["book1"])
print(books.keys())
print(books.values())
```

# Interview One-Liners

-   List → Mutable
-   Tuple → Immutable
-   Set → No Duplicates
-   Dictionary → Key-Value Pair
-   Python is dynamically typed.
-   Index starts from 0.
-   Python uses indentation instead of braces.
