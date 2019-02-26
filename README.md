# calculator
  python coded calculator

print ("Hello")
print ("Type 'exit' to end calculator")

continue1 = True

while (continue1):

#just

	invalid = False

#main function

	task = input("+ or - or * or / :")

#addition

	if (task == "+"):
	
		num1 = float(input ("enter first number:"))
		num2 = float(input ("enter second number:"))

		add = num1 + num2
		if (add % 1 == 0):
			add = int(add)

		print (add)

#subtraction

	elif (task == "-"):

		num1 = float(input ("enter first number:"))
		num2 = float(input ("enter second number:"))

		add = num1 - num2
		if (add % 1 == 0):
			add = int(add)

		print (add)

#multiplication

	elif (task == "*"):

		num1 = float(input ("enter first number:"))
		num2 = float(input ("enter second number:"))

		add = num1 * num2
		if (add % 1 == 0):
			add = int(add)

		print (add)

#division

	elif (task == "/"):

		num1 = float(input ("enter first number:"))
		num2 = float(input ("enter second number:"))

		add = num1 / num2
		if (add % 1 == 0):
			add = int(add)

		print (add)
	
	elif (task == "exit"):
		continue1 = False
		invalid = True


	else:

		print ("invalid input")
		invalid = True	

	if (invalid == False):
		print ("Your calculation has been completed")

print ("finished?")
print ("bye")
