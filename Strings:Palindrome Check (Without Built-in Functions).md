# Ex-3D TUPLES
## Aim
To write a python program to create the tuple by the multiples of 9 up to N and the print length of the tuple.
## ALGORITHM:
1.	Read input and convert it to an integer, storing it in variable "r".
2.	Create a tuple "tup" containing multiples of 9, starting from 9 and ending at "r" (exclusive), using a generator expression inside the tuple.
3.	Print the tuple "tup".
4.	Print the length of the tuple "tup" using a formatted string and the "len" function.
5.	End of the program.
## PROGRAM:
```
r = int(input())
tup = tuple(i for i in range(9,r,9)) 
print(tup)
print(f"Length of the tuple is {len(tup)}")
```
## Output
![Screenshot (73)](https://github.com/user-attachments/assets/8c136018-c568-4670-9ff0-4111bba19230)

## Result
Thus, the required program is written and executed successfully.
