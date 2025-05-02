# Ex-3B REGEX
## Aim
To write a Python program to find sequences of lowercase letters joined with a underscore.
## Algorithm
1.	Import the "re" module.
2.	Read input and store it in variable "inp".
3.	Define a regular expression pattern "pattern" to match strings of lowercase letters separated by an underscore.
4.	Use the "match" function from the "re" module to search for a match between the pattern and the input string.
5.	Check if a match is found:
a.	If true, print "Found a match!".
b.	If false, print "Not matched!".
6.	End of the program.
## Program
```
import re inp = input()
pattern = r'[a-z]+_[a-z]+' match = re.match(pattern,inp) if match:
print("Found a match!") else:
print("Not matched!")
```
## Output
![Screenshot (71)](https://github.com/user-attachments/assets/ba027e12-2969-428f-94ba-7e3dc9c6c76d)
## Result
Thus, the required program is written and executed successfully.
