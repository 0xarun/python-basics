**Multiple statements in one line**

	a=2;b=3;c=a+b;print(c)
	OUTPUT : 5

**Membership operator:**
	
	x=1
	y=2
	list=[2,3,5,6,7]
	if(x in list):
	    print("x is available in list")
	else:
	    print("X not in list")
	    if(y in list):
		print("y is available in list")
	    else:
		print("y not in list")
	OUTPUT : 
	X not in list
	y is available in list

**Boolean operators :**

	a=True
	b=False
	print(a and b)
	print(a or b)
	print(not a)
	print(not b)

	OUTPUT :

	False
	True
	False
	True

### Sequential Statements 

**Addition of two numbers**

	a=int(input("Enter number 1 :"))
	b=int(input("Enter number 2 :"))
	c=a+b
	print("Answer is",c)

**Area of circle**

    r=int(input("Enter the radius"))
    area =3.14*r*r
    print("Area of circle is ",(area))
    Area of square
    side=int(input("Enter side value"))
    area=side*side
    print(area)

**Area of rectangle**
   
    l=int(input("Enter the length :"))
    b=int(input("Enter the breadth :"))
    area=l*b
    print("Area of reactangle is",area)
    • Calculate Simple Interest
    • Find Total and average of given 5 marks
    • Print square of a number

### Selective statements 
**Biggest of two numbers**

    a=int(input("Enter value of a:"))
    b=int(input("Enter value of b:"))
    if(a>b):
        print("a is greater")
    else:
        print("b is greater")
    Find leap year
    year=int(input("Enter the year"))
    if((year%4)==0):
        print("The year is leap year")
    else:
        print("The year is not leap year")

**Negative or positive number**

	a=int(input("Enter a number"))
	if(a>0):
	    print("The number is positive")
	elif(a<0):
	    print("the number is negative")
	else:
	    print("Number is zero")

**Odd or Even**

	a=int(input("Enter a number"))
	if((a%2)==0):
	    print("The number is even")
	else:
	    print("The number is odd")

**Find biggest of 3 numbers**

	a=int(input("Enter number 1:"))
	b=int(input("Enter number 2:"))
	c=int(input("Enter number 3:"))
	if((a>b)&(a>c)):
	    print("A is greater")
	elif((b>c)&(b>a)):
	    print("B is greater")
	elif((c>a)&(c>b)):
	    print("c is greater")

**Looping Statements**

Print n natural numbers

	n=int(input("Enter  n value :"))

	print("\n")
	for i in range(0,n,1):
	    print(i)
	Print n odd numbers
	n=int(input("Enter  n value :"))

	print("\n")
	for i in range(1,n,2):
	    print(i)
	Print n even numbers
	n=int(input("Enter  n value :"))

	print("\n")
	for i in range(0,n,2):
	    print(i)

**Print squares of n numbers**

    n=int(input("enter n value:"))
    print("Square numbers upto",n)
    for i in range(1,n+1,1):
       	 s=i*i
        	print(s)

    OUTPUT :
    enter n value:
    5 
    Square numbers upto 5 
    1 4 9 16 25 

**Sum of n numbers**

	n=int(input("enter n value:"))
	sum=0
	print("Sum of numbers upto",n)
	for i in range(1,n+1,1):
	    sum=sum+i
	print(sum)
	OUTPUT :
	enter n value:
	5 
	Sum of numbers upto 5 
	15

**Print factorial of a given number**

    n=int(input("enter n value:"))
    fact=1
    print("Factorial of",n ,"is")
    for i in range(1,n+1,1):
        fact=fact*i
    print(fact)
    OUTPUT :
    enter n value:
    4 
    Factorial of 4 is 24

### Illustrative Programs

**1. Program to circulate values of n variables**

	list=[11,13,15,17,18]
	print(list)
	for i in range(1,5,1):
	    list1=list[i:]+list[:i]
	    i=i+1
	    print(list1)

	OUTPUT :
	[11, 13, 15, 17, 18] 
	[13, 15, 17, 18, 11] 
	[15, 17, 18, 11, 13] 
	[17, 18, 11, 13, 15]
	[18, 11, 13, 15, 17]

**2. Swapping of 2 values**


	a=int(input("Enter value 1:"))
	b=int(input("Enter value 2: "))
	print("Before swapping")
	print("a =",a)
	print("b =",b)
	print("After swapping")
	t=a
	a=b
	b=t  
	print("a=",a)
	print("b=",b)

	OUTPUT :
	Enter value 1:
	4 
	Enter value 2: 
	6 
	Before swapping 
	a = 4 
	b = 6 
	After swapping 
	a= 6 
	b= 4 
       
**3. Distance between two points :**

    x1,y1=eval(input("Enter x1 and y1 values:"))
    x2,y2=eval(input("Enter x2 and y2 values:"))
    d=(((x1-x2)*(x1-x2))+((y1-y2)*(y1-y2))**0.5)

    print("The distance between two points :")
    print(d)

    OUTPUT :
    Enter x1 and y1 values:
    1,2 
    Enter x2 and y2 values:
    2,3 
    The distance between two points : 2.0

**Find the minimum in the given list**


       list=[12,14,15,17,10]
       min=list[0]
       for i in range(0,5,1):
           if(list[i]<=min):
               min=list[i]
       print("Minimum in the list is",min)
       OUTPUT :
       Minimum in the list is 10
       
      Create a list from user and circulate
       
       list=[]
       n=int(input("Enter N:"))
       for i in range(0,n,1):
           list.append(int(input()))
       print(list)
       for j in range(0,n,1):
           list1=list[j:]+list[:j]
           print(list1)
       OUTPUT :
       
    Enter N:
    4 
    1 
    2 
    3 
    4 
    [1, 2, 3, 4] [1, 2, 3, 4] [2, 3, 4, 1] [3, 4, 1, 2] [4, 1, 2, 3] 
  

**LIST OPERATIONS**

	_#create an empty list_

	list=[]
	n=int(input("Enter N:"))

	_#create a list from user input_

	for i in range(0,n,1):
	    list.append(int(input()))
	    print(list)
	    # calculate sum
	    print(sum(list))
	    # calculate length of a list
	    print(len(list))
	    # sort a list
	    list.sort()
	    print(list)
	       #Add an element in to a list
	    list=[8,23,6,21,1]
	    a=int(input("add element"))
	    list.append(a)
	    list.sort()
	    print(list)
	    # Find minimum in the list
	    list=[8,23,6,21,1]
	    a=min(list)
	    print(a)

**To find a character is a vowel or not**

	v=['a','e','i','o','u']
	c=input("Enter an alphabet")
	if(c in v):
	    print(c,"is a vowel")
	else:
	    print("Not a vowel")

**Fahrenheit to celcius conversion**


    °F = °C * 1.8000 + 32.00
	
    Absolute Zero
    -273.15°C
    -459.67°F
    Parity
    -40.00°C
    -40°F
    Freezing point
    0°C
    32°F
    Body Temperature
    37°C
    98.6°F
    Boiling point
    100°C
    212°F

    c=float(input("enter a number"))
    f=(c*1.8)+32

**Total Rupees calculation**

    a=int(input("10 rupees coins:"))
    b=int(input("5 rupees coins:"))
    c=int(input("2 rupees coins:"))
    d=int(input("1 rupee coins:"))
    total=((a*10)+(b*5)+(c*2)+(d*1))
    print("total =",total,"rupees")

**Decimal - Binary conversion**

	n=int(input("Enter a number :"))
	b=oct(n)
	print(b)
       
**Counting the no, of even and odd numbers In a list :**
       
       ocount=0
       ecount=0
       list=[]
       n=int(input("Enter the size of list:"))
       for i in range(0,n,1):
           list.append(int(input()))
           print(list)
           if(((list[i])%2)==0):
               print(list[i],":Even")
               ocount=ocount+1
           else:
               print(list[i],":Odd")
               ecount=ecount+1
       print(ocount)
       print(ecount)

**Vowel or not (without using membership operator)**

	list=[]
	for i in range(0,5,1):
	    v=input("Enter vowels:")
	    list.append(v)
	print(list)
	c=input("enter a character")
	for j in range(0,5,1):
	    if(list[j]==c):
		vowel=1
	    else:
		vowel=0    
	if(vowel==1):
	    print(c,"is a vowel")
	elif(vowel==0):
	    print(c,"is not a vowel")
