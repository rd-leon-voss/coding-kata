Certainly! Here's the coding kata for Roman Numeral Conversion in markdown format:

# Roman Numeral Conversion

## Problem Statement
Write a function that takes a Roman numeral as input and converts it to an integer. The input will be a valid Roman numeral representation.

Roman numerals are represented by a combination of letters from the Latin alphabet. The following letters and their respective values are used:

| Symbol | Value |
|--------|-------|
| I      | 1     |
| V      | 5     |
| X      | 10    |
| L      | 50    |
| C      | 100   |
| D      | 500   |
| M      | 1000  |

To represent numbers, the Roman numerals are combined in the following ways:
- "I" can be placed before "V" (5) and "X" (10) to make 4 and 9.
- "X" can be placed before "L" (50) and "C" (100) to make 40 and 90.
- "C" can be placed before "D" (500) and "M" (1000) to make 400 and 900.

## Function Signature
```python
def roman_to_integer(roman: str) -> int:
    # Your code here
    pass
```

## Examples
Input: "III"
Output: 3

Input: "IV"
Output: 4

Input: "IX"
Output: 9

Input: "LVIII"
Output: 58

Input: "MCMXCIV"
Output: 1994

## Constraints
- The input will be a valid Roman numeral representation.
- The input string will consist only of uppercase letters.
- The value of the Roman numeral will be within the range from 1 to 3999.

Write your solution in the provided `roman_to_integer` function. You can create additional helper functions if needed.

Test your implementation using the given examples to ensure your function works as expected.

Feel free to ask if you have any questions. Happy coding!