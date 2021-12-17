## BASIC PROGRAMMING IN PYTHON

1. Print(“Hai… My First Program in Python”)

2. a=10
Print(a)

OUTPUT : 10

3. x=546.75
print(x)

OUTPUT : 546.75

4. x='a'
print(x)

OUTPUT : a

5. a=”apple”
print(a)

OUTPUT : apple

###CONVERSION BETWEEN DATA TYPES

**Floating point to Integer Convesion**
6. b=int(75.65)
print(b)

OUTPUT : 75

**Integer to Floating Point Conversion**
7. b=float(20)
print(b)

OUTPUT : 20.0

###ADDITION OF TWO NUMBERS

**INTEGER ADDITION**

8. a=10
b=79
c=a+b
print(c)

OUTPUT : 89

**FLOATING POINT ADDITION**
9. a=78.9
b=23.4
c=a+b
print(c)

OUTPUT : 102.30000000000001

**COMPLEX NUMBER ADDITION**

10. a=45+2j
b=4+2j
c=a+b
print(c)

OUTPUT : 49+4j

11. BOOLEAN TYPE

print(2<3)
print(2>3)
print(5==5)
print(7!=5)
print(34==6)

OUTPUT : 
True
False
True
True
False

###STRING MANIPULATION

12.  a=’python’
b=’programming’
print(a+b)

OUTPUT : pythonprogramming

13. a='python'
b='\t'
c='programming'
print(a+b+c)

OUTPUT : python programming

14. String Repetition
a='python'
print(a*3)

OUTPUT : pythonpythonpython

15. a='python programming'
print(a[0:10])

OUTPUT  :  python prog

16. a='python programming'
print(a[3:10])

OUTPUT  :  hon pro

17. a='python'
b='program'
print("I am doing my first",a,b)

OUTPUT : I am doing my first python program

18. a='python program'
print(a[6:]+'ming')

OUTPUT : programming

19. a='python program'
print(a[-4])

OUTPUT : g

20. a='python program'
print(a[2])

OUTPUT : t

###LIST MANIPULATION


Creating a list : 

21. list=[1,'kumar','chennai','m',20]
print(list)

OUTPUT : [1, 'kumar', 'chennai', 'm', 20]

22. print(list[1])
OUTPUT : kumar

23. print(list[1:3])
OUTPUT : ['kumar', 'chennai']

24. print(list[2:])
OUTPUT : ['chennai', 'm', 20]

25. print(list[:2])
OUTPUT : [1, 'kumar']

26. list1=[1,'saravanan','trichy','m',20]
list2=[2,'siva','chennai','m',21]
list3=[3,'geetha','bangalore','f',20]
print(list1+list2+list3)

OUTPUT  :  [1, 'saravanan', 'trichy', 'm', 20, 2, 'siva', 'chennai', 'm', 21, 3, 'geetha', 'bangalore', 'f', 20]

27. list1=[1,'saravanan','trichy','m',20]
list2=[2,'siva','chennai','m',21]
list3=[3,'geetha','bangalore','f',20]
print(list1) 
print(list2)
print(list3)

OUTPUT : 
[1, 'saravanan', 'trichy', 'm', 20]
[2, 'siva', 'chennai', 'm', 21]
[3, 'geetha', 'bangalore', 'f', 20]

### MANIPULATION WITH TUPLES

28. t1=(1,'saravanan','trichy','m',20)
t2=(2,'siva','chennai','m',21)
print(t1+t2)

OUTPUT : (1, 'saravanan', 'trichy', 'm', 20, 2, 'siva', 'chennai', 'm', 21)

29. t1=(1,'saravanan','trichy','m',20)
t2=(2,'siva','chennai','m',21)
print(t1[1],t1[2],t2[1],t2[2])

OUTPUT : saravanan trichy siva Chennai

30. t=(1,'saravanan','trichy','m',20)
print(t[2:])

OUTPUT : ('trichy', 'm', 20)

MANIPULATION WITH SETS

31. x=set("python")
print(x)

OUTPUT : {'t', 'o', 'h', 'p', 'y', 'n'}

32. x=set("python programming ")
print(x)

OUTPUT : {'a', 't', 'o', 'm', 'h', 'r', 'p', 'y', 'i', 'g', ' ', 'n'}

33. x=set(("chennai","bangalore","coimbatore","trichy","chennai","bangalore","trichy"))
print(x)

OUTPUT : {'coimbatore', 'chennai', 'bangalore', 'trichy'}

###DICTIONARIES – MAPPING

34. dictionary={'name':'lakshmi','roll':'234','dept':'CSE'}
print(dictionary)
print(dictionary.keys())
print(dictionary.values())

OUTPUT : 

{'name': 'lakshmi', 'roll': '234', 'dept': 'CSE'}
dict_keys(['name', 'roll', 'dept'])
dict_values(['lakshmi', '234', 'CSE'])


