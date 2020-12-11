
# Python program to find the largest number among the four input numbers

number1 = int(input("Enter the 1st number : "))
number2 = int(input("Enter the 2nd number : "))
number3 = int(input("Enter the 3rd number : "))
number4 = int(input("Enter the 4th number : "))

if (number1 >= number2 ) and ( number1 >= number3 ) and (number1 >= number4):
    largest = number1
elif (number2 >= number1 ) and (number2 >= number3) and (number2 >= number4):
    largest = number2
elif (number3 >= number1) and (number3 >= number2) and (number3 >= number4):
    largest = number3
else:
    largest = number4


print(f" The largest number of the list is \n{largest}")
