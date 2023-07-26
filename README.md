# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: ABISHAI K C
RegisterNumber: 23001564
'''
def max_marks(marks):
    marks.sort()
    return marks[9]
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: ABISHAI K C 
RegisterNumber: 23001564
'''
def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 
'''
def max_marks(list1):
    maximum = list1[0] 
    for i in list1:
        if i>maximum:
            maximum = i
        else:
            continue
    return maximum
```
## Sample Input and Output
### Using Sort Function
![output](/sort%20output.png)
### Using Max Function
![output](/max%20output.png) 
### Without Using Any Built-In Function
![output](/Screenshot%202023-07-26%20182101.png) 


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.