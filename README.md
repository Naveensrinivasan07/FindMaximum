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
Developed by: NAVEEN S
RegisterNumber: 212222240070
'''
def max_marks(marks):
    marks.sort()
    b=marks[-1]
    return b


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: NAVEEN S
RegisterNumber: 212222240070
'''
def max_marks(marks):
    a=max(marks)
    return a
    


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: NAVEEN S
RegisterNumber: 212222240070
'''
def max_marks(list1):
    for i in list1:
        if i>94:
            return i
           


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![output1](![OUTPUT](https://github.com/Naveensrinivasan07/FindMaximum/assets/119475891/0744ecae-9726-42a7-aca8-cfa0498679eb)
![output2](![OUTPUT 3](https://github.com/Naveensrinivasan07/FindMaximum/assets/119475891/ae5f74b5-1402-4dcc-b307-fb43e21b9f2b)







## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
