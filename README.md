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
#Program to mark the maximum of marks using the list method sort.
#Program Developed by: KRISHNA KUMAR R
#Register Number: 212223230107
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
#Program to find the maximum marks using the list method max().
#Program developed by: KRISHNA KUMAR R
#Register No: 212223230107
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
#Program to find the maximum marks without using builtin functions.
#Program developed by: KRISHNA KUMAR R
#Register No: 212223230107
def max_marks(marks):
    max_mark=0
    for i in marks:
        if i>max_mark:
            max_mark=i
    return max_mark
```

## Output:

![Screenshot 2024-04-05 114720](https://github.com/Krishna23013541/FindMaximum/assets/149557764/67777cf4-ad38-49d0-b928-92373093f79a)

![Screenshot 2024-04-05 114743](https://github.com/Krishna23013541/FindMaximum/assets/149557764/236b398a-9765-4b2d-ad13-d139b1a4e93a)

![Screenshot 2024-04-05 114800](https://github.com/Krishna23013541/FindMaximum/assets/149557764/ce43cb62-374a-45a2-a125-2da5f3a7689f)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
