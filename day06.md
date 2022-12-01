<div align="center">
  <h1>Day 6</h1>

  <sub>
    Author: <a href="https://github.com/nohinlab" target="_blank">Nohin</a>
    <br>
    <small>Nov 13, 2022 - Sunday</small>
  </sub>
</div>

[<< Day 5](day05.md) | [Day 7 >>](day07.md)

## My Progress :
* Chapter 9 - 24/56 Videos

## Notes :
<details>
<summary>Python Dictionaries</summary>

- Dictionaries allow doing fast databae-like operations in Python.
```python
items = dict({"key1": 1, "key2": 2, "key3": 3})
items["key4"] # error if key4 is not present
"key4" in items # check if key4 is present
```
- Common Applications
  - Counting the frequency of things.
  ```python
  counts = dict()
  names = ["csev", "cwen", "csev", "zqian", "cwen"]
  for name in names:
      if name not in counts:
          counts[name] = 1
      else:
          counts[name] += 1
  ```
  Using `get()` method
  ```python
  if name in counts:
      x = counts[name]
  else:
      x = 0
  # can be written as
  x = counts.get(name, 0)
  ```
  ```python
  counts = dict()
  names = ["csev", "cwen", "csev", "zqian", "cwen"]
  for name in names:
      counts[name] = counts.get(name, 0) + 1
  ```

- Dictionaries and Loops
  - for key in dictionary
  - for key, value in dictionary.items()



</details>
