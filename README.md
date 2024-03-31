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
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    max_marks=max(marks)
    return max_marks


```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(marks):
    max= marks[0]
    for i in marks[1:]:
        if i > max:
            max = i
    return max


```


## Output:
i)

![Screenshot 2024-03-31 174648](https://github.com/VincyJovitha01/FindMaximum/assets/147121113/3b538ba3-9900-40f9-ab11-139b13676887)

ii)

![image](https://github.com/VincyJovitha01/FindMaximum/assets/147121113/ece115af-c7b2-4557-af75-1c794dbf88a4)

iii)

![image](https://github.com/VincyJovitha01/FindMaximum/assets/147121113/2ed2c29b-2ace-4983-a059-21b89e8daa85)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
