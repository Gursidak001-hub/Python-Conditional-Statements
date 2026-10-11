    # 06. Grade Calculator
    # Input marks from 0–100. Assign grades: A (90–100), B (75–89), C (60–74), D (40–59), F (below 40). Reject invalid marks.
    
    Marks=float(input("Enter Your Marks (0-100)"))
    if(Marks<0 or Marks>100):
        print("Invalid Marks")
    elif (Marks>=90):
        print("Grade A")
    elif (Marks>=75):
        print("Grade B")
    elif (Marks>=60):
        print("Grade C")
    elif (Marks>=40):
        print("Grade D")
    else:
        print("Grade F")
        




    #07. Largest of Three Numbers
    #Input three numbers and find the largest. Handle equal values correctly.
    Number1=float(input("Enter First Number"))
    Number2=float(input("Enter Second Number"))            
    Number3=float(input("Enter Third Number"))
    if(Number1>Number2 and Number1>Number3):
        print("The First Number is Largest",Number1)
    elif(Number2>Number1 and Number2>Number3):
        print("The Second Number is Largest", Number2)
    elif(Number3>Number1 and Number3>Number1):
        print("The Third Number is Largest", Number3)
    else:
        print("Two or more Largest values are Equal")
        
    



    #08. Leap Year Checker
    #Check whether a year is a leap year using the standard Gregorian calendar rules.
    Year=int(input("Enter Year: "))
    if(Year % 4 == 0 and Year % 100 != 0) or (Year % 400 == 0):
             print("Leap Year")
    else:
             print("Not a Leap Year")
    
    




    #09. Simple Calculator
    #Input two numbers and an operator (+, -, *, /). Perform the operation and handle division by zero.
    Number1=float(input("Enter a Number"))
    Number2=float(input("Enter a Number"))
    operator=input("Enter the operator (+, -, *, /):")
    if(operator == "+"):
        print("Result" , Number1+Number2)
    elif (operator == "-"):
        print("Result", Number1-Number2)
    elif (operator == "*"):
        print("Result", Number1*Number2)
    elif(operator == "/"):
        if(Number2 != 0):
            print(Number1 / Number2)
        else:    
            print("Error: Cannot divide by zero")
    else:
        print("Invalid Operator")
            
    




    #10. Temperature Category
    #Input temperature in Celsius. Classify it as below freezing (<0), cold (0–15), moderate (16–25), hot (26–35), or very hot (>35).
    
    Temperature=float(input("Enter the Temperature"))
    if Temperature<0:
        print("Freezing")
    elif Temperature<=15:
        print("Cold")
    elif Temperature<=25:
        print("Moderate")
    elif Temperature<=35:
        print("Hot")
    else:
        print("Very Hot")



    

