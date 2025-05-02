# Ex-3C LISTS
## Aim
To write a python program to display the duplicate items of the user entered list.
## Algorithm
1.	Read input and evaluate it as a list, storing it in variable "li".
2.	Initialize an empty list "dli" to store duplicate items.
3.	Start a loop to iterate through each element in the input list "li":
    a. Check if the count of the current element in the list is greater than 1 and the element is not already in the list "dli":
i.	If true, append the element to the list "dli".
4.	Print the list "dli" containing duplicate items using a formatted string.
5.	End of the program
## Program
```
li = eval(input()) dli = []
for el in li:
   if li.count(el)>1 and el not in dli:
      dli.append(el)
print(f"Duplicate items list : {dli}")
```
## Output
![Screenshot (72)](https://github.com/user-attachments/assets/bf872cbe-609b-4ce9-adce-fd695e339a06)
## Result
Thus, the required program is written and executed successfully.
