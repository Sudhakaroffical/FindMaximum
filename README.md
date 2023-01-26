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
Program to mark the maximum of marks using the list method sort
Developed by: SUDHAKAR K
RegisterNumber: 22007876
'''
def max_marks(list1):
    temp=0
    for i in list1:
        if(temp<i):
            temp=i
    return temp


```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: SUDHAKAR K
RegisterNumber: 22007876
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: SUDHAKAR K
RegisterNumber: 22007876
'''
def max_marks(list1):
    temp=0
    for i in list1:
        if(temp<i):
            temp=i
    return temp



```
## Sample Input and Output
![output](./output3.png)
## code 2
![output](./output3.png)
## code 3
![output](./output3.png)

## Output:

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.