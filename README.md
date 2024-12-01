# BMI-Calculator

## Project Overview
The aim of this project was to demonstrate the functionality of python in executing mundane tasks such as mathematical calculations. With my knowledge of python and its many functions, statements, etc, I was able to code a 'basic' and functional and reactive BMI calculator. 

## Tools
- Jupyter Notebooks

## Brief Walkthrough
- The formula for BMI in this project is (weight (kg))/height * height(m)).
- So, to get started, I first had to create and assign values to the variables in the formula.
```
weight = int(input("weight in kgs: "))
```
- Since the height in metres, wrap the above line of code with float() instead of int() because metres would be in decimal fractions. If you choose centimetres, then you can stick with int() but the formula would include '*10000'.
```
height = float(input("height in metres: ")
```
<small> Note: I genuinely feel like I am preaching to the choir here, I promise i do not intend to ramble, i just worry i do not know the etiquette here so i just explain even the tiniest steps.</small>

- After which I created if, elif and else statements that would run depending on the corresponding results of the BMI calculation. These statements of coruse are accompanied by prompt texts.
```
if BMI>0:
    if(BMI<18.5):
        print(name +", yo, get your protein up!.")
    elif (BMI<=24.9):
        print(name +", yo, you're in that sweet spot.")
    elif (BMI<29.9):
        print(name +", you have strayed from the sweet spot.")
    elif (BMI<34.9):
        print(name +", you are obese.")
    elif (BMI<39.9):
        print(name +", you are severely obese.")
    elif (BMI>40):
        print(name +", you are morbidly obese.")
else:
    print("Enter valid input")
```

🃏
