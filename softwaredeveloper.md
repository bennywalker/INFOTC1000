# Software Developer
![Software image](https://itchronicles.com/wp-content/uploads/2020/09/software-dev-languages.jpg)

## Information About Software Developer
1. [Salary: $100k](https://builtin.com/salaries/design-ux/ux-designer)
2. [Where I want to work: Denver or Colorado Springs](https://www.valuepenguin.com/mortgages/best-cities-for-software-developers)

## Why I am interested in Software Development
I consider myself a fairly creative person, so with Software Development, like UX Design, I can use my creative thinking as well as my love for technology to futher advance systems to make them more efficient. I find great satisfaction in streamlining programs.

## My Sample Code:
import math

def cone_calculator ():

    while True:
        try:
            r=float(input("What is the radius? "))
            if r < 0:
                 print("Input must be a POSITIVE integer. Try again. ")
            elif r > 0:
                r=r+0
                break
        except (ValueError):
            print("Input must be a positive INTEGER. Try again. ")

    while True:
        try:
            h=float(input("What is the height? "))
            if h < 0:
                print("Input must be a POSITIVE integer. Try again.  ")
            elif h > 0:
                h=h+0
                break
        except (ValueError):
            print("Input must be a positive INTEGER. Try again. ")

    volume_cone=math.pi*r*r*h/3
    print("The volume of your cone is:", str(volume_cone))
    input_2()

def cylinder_calculator ():

    while True:
        try:
             r = float(input("What is the radius? "))
             if r < 0:
                print("Input must be a POSITIVE integer. Try again. ")
             elif r > 0:
                r = r + 0
                break
        except (ValueError):
            print("Input must be a positive INTEGER. Try again. ")

    while True:
        try:
            h = float(input("What is the height? "))
            if h < 0:
                print("Input must be a POSITIVE integer. Try again.  ")
            elif h > 0:
                h = h + 0
                break
        except (ValueError):
            print("Input must be a positive INTEGER. Try again. ")
    volume_cone = math.pi * r * r * h
    print("The volume of your cylinder is:", str(volume_cone))
    input_2()

def cube_calculator ():

    while True:
        try:
             s = float(input("What is the length of one side? "))
             if s < 0:
                print("Input must be a POSITIVE integer. Try again. ")
             elif s > 0:
                s = s + 0
                break
        except (ValueError):
            print("Input must be a positive INTEGER. Try again. ")

    volume_cube = s * s * s
    print("The volume of your cube is:", str(volume_cube))
    input_2()

def calculator_selector ():
    while True:
        i = input("What would you like to calculate? Type 'cone' 'cylinder' or 'cube' ")
        if i == 'cone':
            cone_calculator()
        elif i == 'cylinder':
            cylinder_calculator()
        elif i == 'cube':
            cube_calculator()
            break
        else:
            print("Input must be either 'cone' cylinder' or cube'. Try again")

def start_input ():
    start=input("Hello user. Type 'y' if you would like to perform a calculation. ")
    if start== 'y':
        calculator_selector ()
    else:
        print("Ok. Have a good day. ")
        exit()

def input_2 ():
    a = input("Type 'y' if you would like to make another calculation. ")
    if a == 'y':
        calculator_selector()
    else:
        print("Have a good day. ")
        exit()

start_input()]

### Last Page
[Last](uxdesigner.markdown)
### Return to homepage
[Here](README.md)