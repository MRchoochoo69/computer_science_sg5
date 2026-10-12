#Sean Francis Castro Cacatian/Dahlia-6 Distance Calculator

#Import Math module
import math

#Check if string can be converted to integer 
def int_check(stri):
  try:
    int(stri)
    return True
  except ValueError:
    return False

#Ask for coodinates of the first point
x1_str = input("Enter X1: ")
y1_str = input("Enter Y1: ")

#Ask for coodinates of the second point
x2_str = input("Enter X2: ")
y2_str = input("Enter Y2: ")

#Convert input coordinates into integers
if not (int_check(x1_str) and int_check(y1_str) and int_check(x2_str) and int_check(y2_str)):
  print("Error: Invalid Coordinate Input.")
else:
  x1 = int(x1_str)
  y1 = int(y1_str)
  x2 = int(x2_str)
  y2 = int(y2_str)

  #Calculate distance between points
  dist = math.sqrt(math.pow(x1 - x2, 2) + math.pow(y1 - y2, 2))

  #Display distance
  print("Distance: ", str(dist))
