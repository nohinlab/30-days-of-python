<div align="center">
  <h1>Day 5</h1>

  <sub>
    Author: <a href="https://github.com/nohinlab" target="_blank">Nohin</a>
    <br>
    <small>Nov 12, 2022 - Saturday</small>
  </sub>
</div>

[<< Day 4](day04.md) | [Day 6 >>](day06.md)

## My Progress :
* Chapter 6 - 16/56 Videos
* Chapter 7 - 18/56 Videos
* Chapter 8 - 21/56 Videos

## Notes :
<details>
<summary>Strings</summary>

- Strings are immutable
- string have length : len(string) 
- loop through string
```python
string = "Hello"
index = 0
while index < len(string):
    letter = string[index]
    print(letter)
    index += 1
```

```python
string = "Hello"
for letter in string:
    print(letter)
```

- Using colon operator for string slicing

- Using 'in' as a logical operator`

- Using string methods:
    ```python
    string = "Hello"
    print(string.lower())
    print(string.upper())
    # to see all methods
    dir(string)
    ```
</details>

<details>
    <summary>Reading Files</summary>

* ### Opening a file
open() function returns a file handle, a variables used to perform operations on the file. This is similat to file -> open in a word processor.
```python
file_handle = open('file_name.txt', 'r')
```
```  
\n is a newline character .
Newline is one character.
```
* ### Reading a file
    - A file handle can be seen ad a sequence of strings, each line in the file is a string in the sequence. We can use a for loop to iterate through the sequence.
    - We can also use the read() method to read the entire file at once.
    ``
    file_handle = open('file_name.txt')
    file_handle.read()
    ``
</details>

<details>
    <summary>Python Lists</summary>

- A list element can be any type of object, including another list.
- Lists are mutable, meaning their elements can be changed.
- Concatenating list using + operator
- List slicing using colon operator
</details>

<details>
<summary>Strings and Lists</summary>

```python
abc = 'With three words'
words = abc.split()
print(words)
```
```
['With', 'three', 'words']
```
```python
num_words = len(words)
print(num_words)
```
```
3
```
</details>

## Codes :
* No codes today

## Resources :
* <a href="https://www.freecodecamp.org/learn/scientific-computing-with-python/#python-for-everybody" target="_blank">Scientific computing with python by freecodecamp</a>
