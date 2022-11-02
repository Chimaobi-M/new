# new
Python journey
# a simple calculator
def calculate(first, sign, second):
    if sign== "+":
        result= first + second
        print(result)
    elif sign== "-":
        result= first - second
        print(result)
    elif sign== "/":
        result= first/second
        print(result)
    elif sign== "*":
        result= first * second
        print(result)
    else:
        raise TypeError("input a correct math symbol")

first= int(input("please enter a number"))
sign=input("please enter a math operator symbol")
second= int(input("please enter another number"))
calculate(first, second, sign)
