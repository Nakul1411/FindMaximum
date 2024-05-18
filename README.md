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
#DEVELOPED BY: NAKUL R
#REGISTRATION NUMBER: 212223240102
def max_marks(array):
    array.sort()
    return array[-1] 
```

ii)	# To find the maximum marks using the list method max().
```Python
#DEVELOPED BY : NAKUL R
#REGISTRATION NUMBER : 212223240102
def max_marks(array):
    return max(array)
```

iii) # To find the maximum marks without using builtin functions.
```Python
#DEVELOPED BY:NAKUL R
#REGISTRATION NUMBER:212223240102
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1
```



## Output:
![Screenshot 2024-05-18 121145](https://github.com/Nakul1411/FindMaximum/assets/138849780/cd5bd329-5f89-45a5-a2ca-a5892c77b6fd)
![Screenshot 2024-05-18 121159](https://github.com/Nakul1411/FindMaximum/assets/138849780/8b38abf4-e8db-436c-8be8-eb3191de25d7)
![Screenshot 2024-05-18 121210](https://github.com/Nakul1411/FindMaximum/assets/138849780/7693d455-60bb-4622-ae92-6327fdd3584c)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
