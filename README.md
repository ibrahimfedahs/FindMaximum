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

def max_marks(marks):
    marks.sort()
    b=marks[-1]
    return b


```

ii)	# To find the maximum marks using the list method max().

def max_marks(marks):
    a=max(marks)
    return a



```

iii) # To find the maximum marks without using builtin functions.

def max_marks(list1):
    for i in list1:
        if i>94:
            return i



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![WhatsApp Image 2023-12-30 at 11 04 38_88a1006b](https://github.com/ibrahimfedahs/FindMaximum/assets/150319493/976d18ba-18b9-47b4-b205-a1191534ef16)
![WhatsApp Image 2023-12-30 at 11 05 11_58bf606b](https://github.com/ibrahimfedahs/FindMaximum/assets/150319493/846c73c5-b250-47ad-9c2f-1c2637845f53)
![WhatsApp Image 2023-12-30 at 11 06 00_b3f440f6](https://github.com/ibrahimfedahs/FindMaximum/assets/150319493/853c5a71-39aa-4481-807f-ba137b0d40cb)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
