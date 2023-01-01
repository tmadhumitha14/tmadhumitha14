
PROBLEM SOLVING AND PYTHON PROGRAMMING
EX.NO.3 
    
POSITIVE /NEGATIVE/ZERO
CODE:
n=int(input("Enter any number:"))
if n>0:
    print("The number is positive")
elif n<0:
    print("The number is negative")
else:
    print("The number is zero”)

OUTPUT:
Enter any number: 5
The number is positive
Enter any number:-5
The number is negative
Enter any number:0
The number is zero

2.READ A CHARACTER FROM THE  USER. CHANGE INTO UPPER/LOWER
CODE:
a=str(input("Enter any character:"))
a.lower()
    print(a.lower())
a.upper()
    print(a.upper())
        
OUTPUT:
Enter any character: madhumitha
madhumitha
MADHUMITHA

3.TOTAL SALARY WITH BONUS CALCULATION AND PRINT SALARY , BONUS AND TOTAL AMOUNT
CODE:

s=int(input("Enter your salary:"))
if s>100000:
    bonus= s+s*0.1
    print("Your salary is:",bonus)
elif s<100000:
    bonus=s+s*0.12
    Print("Your salary is:",bonus)
else:
    print("No bonus")
         
OUTPUT:
Enter your salary:  20000
Your salary is : 22400.0        

x
