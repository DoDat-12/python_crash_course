# Chapter 06 Code Note
## Dictionaries
### Functions
1. get()
    ```
   point_value = alien_0.get('points', 'No point value assigned.')
   print(point_value)
   ```

2. items() - return the list of key-value pairs
   ```
   for key, value in user_0.items():
   ```
   
3. keys() - return list of keys
   ```
   for name in for key, value in user_0.items():.keys():
   # or
   # for name in for key, value in user_0.items():
   ```
   
4. values() - return list of values without any keys
   ```
   for language in favorite_languages.values():
       print(language.title())
   ```

### Syntax
1. Define
   ```
   alien_0 = {'color': 'green', 'points': 5}
   ```

2. Modify
    ```
   alien_0['color'] = 'red'  # Changing value
   alien_0['x_position'] = 0  # Add new key-value pair
   ```
   
3. Remove key-value pair
    ```
   del alien_0['points']
   ```
   
## Set - A collection in which each item must be unique
### Syntax
1. set of values
   ```
   for language in set(favorite_languages.values()):
   ```
   
