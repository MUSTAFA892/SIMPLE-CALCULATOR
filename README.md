# mustafa
#calculator
import math


def sum(num1, num2):
  sum = num1 + num2
  return sum


def sub(num1, num2):
  sub = num1 - num2
  return sub


def pro(num1, num2):
  product = num1 * num2
  return product


def div(num1, num2):
  quo = num1 / num2
  return quo


#main
ans = 'y'
while ans == 'y':
  print('''THIS IS A SIMPLE CALCULATOR
   1. ADD
   2. SUBTRACTION
   3. MULTIPLY
   4. DIVISION''')
  n = int(input("Enter your choice:"))
  if n == 1:
    n1 = int(input("Enter the first number:"))
    n2 = int(input("Enter the second number:"))
    print("The sum of the given numbers is:", sum(n1, n2))
  elif n == 2:
    n1 = int(input("Enter the first number:"))
    n2 = int(input("Enter the second number:"))
    print("The difference of the given numbers is:", sub(n1, n2))
  elif n == 3:
    n1 = int(input("Enter the first number is:"))
    n2 = int(input("Enter the second number is:"))
    print("The product of the given number is:", pro(n1, n2))
  elif n == 4:
    n1 = int(input("Enter the first number:"))
    n2 = int(input("Enter th second number:"))
    print("The quotient of the given number is:", div(n1, n2))
  else:
    print("INVALID INPUT!!")
  ans = input("Do you want to continue ? (Y/N)...")
