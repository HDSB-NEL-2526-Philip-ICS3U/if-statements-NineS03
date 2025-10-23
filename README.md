#Author:Nine
#Date: 10/23/2025
#If statement

#Users input angle1
angle1 = int(input("Please enter the first angle: "))
#USers input angle2
angle2 = int(input("Please enter the second angle: "))
#Users input angle3
angle3 = int(input("Please enter the third angle: "))
#Checks if triangle is vaild
if angle1 + angle2 +angle3 == 180:
    print("Triangle is valid")
#Not a triangle
else:
    print("Triangle is not valid")

#Users input angle1
angle1 = int(input("Please enter the first angle: "))
#Users input angle2
angle2 = int(input("Please enter the second angle: "))
#Users input angle3
angle3 = int(input("Please enter the third angle: "))
#Checks if triangle is valid
if angle1 + angle2 +angle3 == 180:
    #Checks if it is an equilateral triangle
    if angle1 == angle2 == angle3:
        print("It is an Equilateral triangle")
    #Checks if it is an isosceles triangle
    elif (angle1 == angle2 and angle1 != angle3) or (angle2 == angle3 and angle2 !=angle1) or (angle1==angle3 and angle1!= angle2):
        print("It is an Isosceles triangle")
    #If it is not both equilateral or isosceles, then it is a scalene triangle
    else:
        print("It is a Scalene triangle")
#Not a triangle
else:
    print("Triangle is not valid")

#Users enter a number of the day
day = input("Enter number between 1-7: ")
#1 is Monday
if day=="1":
    print("Monday")
#2 is Tuesday
elif day=="2":
    print("Tuesday")
#3 is Wednesday
elif day=="3":
    print("Wednesday")
#4 is Thursday
elif day=="4":
    print("Thursday")
#5 is Friday
elif day=="5":
    print("Friday")
#6 is Saturday
elif day=="6":
    print("Saturday")
#7 is Sunday
elif day=="7":
    print("Sunday")
#Invalid number
else:
    print("Invalid number")

#Users enter a temperature
temp = int(input("Enter a temperature in centigrade: "))
#Checks if the temperature is less than 0
if temp<0:
    print("Freezing weather")
#Checks if the temperature is between 0-10
elif temp>=0 and temp < 10:
    print("Very Cold weather")
#Checks if the temperature is between 10-20
elif temp>=10 and temp < 20:
    print("Cold weather")
#Checks if the temperature is between 20-30
elif temp>=20 and temp < 30:
    print("Normal in Temp")
#Checks if the temperature is between 30-40
elif temp>=30 and temp < 40:
    print("Its Hot")
#Temp>40
else:
    print("Its Very Hot")

#Users enter a character
char = input("Enter a character: ")
#Checks if the character is an alphabet
if char == "q" or "w" or "e" or "r" or "t" or "y" or "i" or "o" or "p" or "a" or "s" or "d" or "f" or "g" or "h" or "j" or "k" or "l" or "z" or "x" or "c" or "v" or "b" or "n" or "m":
    print("This is an alphabet")
#Checks if the character is a digit
elif char == "0" or "1" or "2" or "3" or "4" or "5" or "6" or "7" or "8" or "9":
    print("This is a digit")
#Then it is a special character
else:
    print("This is a special character")

#Users enter a digit
digit = input("Enter a digit: ")
#Checks if it is a 0
if digit=="0":
    print("Zero")
#Checks if it is a 1
elif digit=="1":
    print("One")
#Checks if it is a 2
elif digit=="2":
    print("Two")
#Checks if it is a 3
elif digit=="3":
    print("Three")
#Checks if it is a 4
elif digit=="4":
    print("Four")
#Checks if it is a 5
elif digit=="5":
    print("Five")
#Checks if it is a 6
elif digit=="6":
    print("Six")
#Checks if it is a 7
elif digit=="7":
    print("Seven")
#Checks if it is a 8
elif digit=="8":
    print("Eight")
#Checks if it is a 9
elif digit=="9":
    print("Nine")
#Not a digit
else:
    print("This is not a digit")

#Users enter a number of a month
month = input("Enter a number of a month: ")
#1 is January
if month=="1":
    print("January")
#2 is February
elif month=="2":
    print("February")
#3 is March
elif month=="3":
    print("March")
#4 is April
elif month=="4":
    print("April")
#5 is May
elif month=="5":
    print("May")
#6 is June
elif month=="6":
    print("June")
#7 is July
elif month=="7":
    print("July")
#8 is August
elif month=="8":
    print("August")
#9 is September
elif month=="9":
    print("September")
#10 is October
elif month=="10":
    print("October")
#11 is November
elif month=="11":
    print("November")
#12 is December
elif month=="12":
    print("December")
#Invalid number
else:
    print("Invalid number")

