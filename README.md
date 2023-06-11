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
i) # To find the maximum of marks using the list method sort.
![ex3a(a)(p)](https://github.com/Naveensrinivasan07/FindMaximum/assets/119475891/a2f68f8c-a069-4738-a558-a1d1f9f0853c)
ii) # To find the maximum marks using the list method max().
![ex2a(b)(p)](https://github.com/Naveensrinivasan07/FindMaximum/assets/119475891/ced5c8ce-79f1-431c-9395-df59a434d220)
iii) # To find the maximum marks without using builtin functions.
![ex3a(c)(p)](https://github.com/Naveensrinivasan07/FindMaximum/assets/119475891/cc36f5ef-1080-4b93-a3ce-f7872be13245)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
