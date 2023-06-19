# Anagram Check

## Problem Statement
Write a function that takes two strings as input and returns `True` if they are anagrams of each other, and `False` otherwise. Anagrams are strings that contain the same characters, but in a different order.

## Function Signature
```python
def is_anagram(string1: str, string2: str) -> bool:
    # Your code here
    pass
```

## Examples
Input: 
```python
string1 = "listen"
string2 = "silent"
```
Output: `True` (the strings "listen" and "silent" are anagrams)

Input:
```python
string1 = "hello"
string2 = "world"
```
Output: `False` (the strings "hello" and "world" are not anagrams)

Input:
```python
string1 = "Dormitory"
string2 = "dirty room"
```
Output: `True` (the strings "Dormitory" and "dirty room" are anagrams)

## Constraints
- The input strings may contain both uppercase and lowercase letters.
- The strings may contain spaces and punctuation, but they should be ignored when determining if the strings are anagrams.
- The input strings can be empty.
- You can assume that the input will always be valid strings.

Write your solution in the provided `is_anagram` function. You can create additional helper functions if needed.

Test your implementation using the given examples to ensure your function works as expected.

Feel free to ask if you have any questions. Happy coding!

## Test Cases
Test Case 1:
```python
string1 = "listen"
string2 = "silent"
Expected Output: True
```

Test Case 2:
```python
string1 = "hello"
string2 = "world"
Expected Output: False
```

Test Case 3:
```python
string1 = "Dormitory"
string2 = "dirty room"
Expected Output: True
```

Test Case 4:
```python
string1 = "anagram"
string2 = "nagaram"
Expected Output: True
```

Test Case 5:
```python
string1 = "Python"
string2 = "nohtyP"
Expected Output: True
```

Test Case 6:
```python
string1 = "abcdef"
string2 = "abcdefg"
Expected Output: False
```

Test Case 7:
```python
string1 = "12345"
string2 = "54321"
Expected Output: True
```

Test Case 8:
```python
string1 = "racecar"
string2 = "carrace"
Expected Output: True
```

Test Case 9:
```python
string1 = ""
string2 = ""
Expected Output: True
```

Test Case 10:
```python
string1 = "openai"
string2 = "aiopen"
Expected Output: True
```