# Chapter 02 Code Note
## Functions
### List
1. range()
   ```
   for value in range(1, 5):  # print from 1 to 4
       print(value)
   # range(6) - from 0 to 5
   # range(1, 8, 2) - distance each = 2
   ```
2. list()
   ```
   numbers = list(range(1, 6))  # [1, 2, 3, 4, 5]
   ```
3. function for list of numbers
   ```
   digits = [1, 2, 3, 4, 5, 6, 7, 8, 9, 0]
   min(digits)  # 0
   max(digits)  # 9
   sum(digits)  # 45
   ```

## Syntax
1. List comprehensions
   ```
   squares = [value**2 for value in range(1, 11)]
   ```