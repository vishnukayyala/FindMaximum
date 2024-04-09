# Find the maximum of a list of numbers
NAME : VISHNU KM

DEPARTMENT : AI / ML

REG NO : 212223240185

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

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python

def max_marks(marks):
    large=max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max_num=list1[0]
    for i in list1:
        if i>max_num:
            max_num=i
    return max_num
    


```



## Output:

![image](https://github.com/vishnukayyala/FindMaximum/assets/151489368/23a0867f-b7bc-4485-b110-09afefc48642)

![image](https://github.com/vishnukayyala/FindMaximum/assets/151489368/9d9b31fa-a8c1-4721-a372-797a1917193f)


![image](https://github.com/vishnukayyala/FindMaximum/assets/151489368/24c810c1-e30b-49ff-9a4c-3488e1634b2f)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
