# Experiment No: 1e – SEB-To write a Python program to evaluate the Body Mass Index (BMI) of a person and determine their weight

## AIM  
To write a Python program to find the minimum between three integer numbers using a conditional expression (Ternary operator).

## ALGORITHM  
1. Start the program.

2.Prompt the user to input their weight (in kg) and height (in meters).

3.Calculate BMI using the formula BMI = weight / (height * height).

4.Determine and display the weight status based on the BMI value.

## PROGRAM
```python
# Reg.No-212222040145
# Name-SANJAI T
# Write your code here
height=float(input())
weight=int(input())
bmi=weight/(height*height)
if bmi<=18.5:
    print("your BMI {} indicates you are Under weight".format(bmi))
elif bmi<=25:
    print("your BMI {} indicates you are Normal weight".format(bmi))
elif bmi<=30:
    print("your BMI {} indicates you are Over weight".format(bmi))
else:
    print("your BMI {} indicates you are Obese".format(bmi))
```

## OUTPUT
![Screenshot 2025-04-28 135452](https://github.com/user-attachments/assets/9f8c6f82-f38d-46df-ab1a-78b40e048370)

## RESULT
The program successfully calculates BMI and displays the corresponding weight status.
