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
```
#Program to mark the maximum of marks using the list method sort
#Developed by: ponguru aasrith sairam
#RegisterNumber: 23007809

def max_marks(marks):
    marks.sort()
    return marks[-1]
```
ii)	# To find the maximum marks using the list method max().
```
#Program to find the maximum marks using the list method max().
#Developed by: ponguru aasrith sairam
#RegisterNumber: 23007809

def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```
#Program to the maximum marks without using builtin functions.
#Developed by: ponguru aasrith sairam
#RegisterNumber: 23007809

def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
![image](https://github.com/AasrithSairam/FindMaximum/assets/139331438/da5ddf09-f0bf-42cb-aa04-67fd447247c0)
![image](https://github.com/AasrithSairam/FindMaximum/assets/139331438/3f9d4f0d-e696-444f-bdb8-06a8d5a612c3)

## Output:
# i)
![image](https://github.com/AasrithSairam/FindMaximum/assets/139331438/c05d8a90-6e1d-41de-b2d0-95ca52c9ec36)
# ii)
![image](https://github.com/AasrithSairam/FindMaximum/assets/139331438/edf9219c-f41f-4892-9ebd-cb0211f16190)
# iii)
![image](https://github.com/AasrithSairam/FindMaximum/assets/139331438/064b3b46-c3f0-438f-98c6-34d1a5dab958)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
