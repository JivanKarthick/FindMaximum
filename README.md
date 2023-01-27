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
Developed by:Jivan Karthec.B.S
RegisterNumber: 22004763
'''
def max_marks(marks):
        marks.sort()
        return marks[-1]
        
    
    


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by:Jivan Karthec.B.S
RegisterNumber: 22004763
'''
def max_marks(marks):
    large = max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by:Jivan Karthec.B.S
RegisterNumber: 22004763
'''
def max_marks(list1):
    max1=list1[0]
    for i in list1:
        if i >max1:
            max1 = i
    return max1
    


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:

![1](https://user-images.githubusercontent.com/121165867/214062258-6bdfe845-9905-4e3b-8b6d-34ff17ba9a11.png)

![2](https://user-images.githubusercontent.com/121165867/214062307-21a93403-5ab9-4583-ad92-c1f8da1d0c4a.png)

![3](https://user-images.githubusercontent.com/121165867/214062355-1b8ccdd7-7650-4acb-9e11-be8db875d430.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
