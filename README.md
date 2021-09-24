# Leetcode46-Valid-Number

###A valid number can be split up into these components (in order):
```
  A decimal number or an integer.
  (Optional) An 'e' or 'E', followed by an integer.
```
###A decimal number can be split up into these components (in order):
```
  (Optional) A sign character (either '+' or '-').
    One of the following formats:
      One or more digits, followed by a dot '.'.
      One or more digits, followed by a dot '.', followed by one or more digits.
      A dot '.', followed by one or more digits.
```

###An integer can be split up into these components (in order):
```
  (Optional) A sign character (either '+' or '-').
  One or more digits.
```

Valid Numbers: ["2", "0089", "-0.1", "+3.14", "4.", "-.9", "2e10", "-90E3", "3e+7", "+6e-1", "53.5e93", "-123.456e789"]
Invalid Numbers: ["abc", "1a", "1e", "e3", "99e2.5", "--6", "-+3", "95a54e53"].

Given these numbers, the code will determine if they are valid or invalid for any case.

Constraints:
  1 <= String.length <= 20
  String consists of only English letters (both uppercase and lowercase), digits (0-9), plus '+', minus '-', or dot '.'.
