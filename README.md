# Ex - 7 :
# Find the maximum of a list of numbers :
# Date : 17/10/24
## Aim :
To write a program to find the maximum of a list of numbers.
## Equipment’s required :
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm :
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
# Program :
## i) To find the maximum of marks using the list method sort.
```Python
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
```
## ii) To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large = max(marks)
    return large
    
```

## iii) To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max        
```



# Output :
## i) To find the maximum of marks using the list method sort.
![EXP-6_ CR- Maximum of a list of number_ Attempt review _ SEC - Google Chrome 17-10-2024 17_14_51](https://github.com/user-attachments/assets/d5928b6a-8a7a-4cff-9a3e-4ecc0ebb4ad5)
## ii) To find the maximum marks using the list method max().
![EXP-6_ CR- Maximum of a list of number_ Attempt review _ SEC - Google Chrome 17-10-2024 17_15_01](https://github.com/user-attachments/assets/6664ca3f-aa21-4e36-8ac1-3676b45b02c2)
## iii) To find the maximum marks without using builtin functions.
![EXP-6_ CR- Maximum of a list of number_ Attempt review _ SEC - Google Chrome 17-10-2024 17_15_05](https://github.com/user-attachments/assets/f4f4c845-3688-4f6f-973a-f1b055a14e24)

## Result :
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
