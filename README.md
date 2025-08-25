print("helllo world")
#single line comment
"""Multiline
comment
"""
#print is a function here

print("Hello this is shivam jha \n welcome buddy")

#output will be shown in two diffrent lines



#variable

name="shivam" #it is a variable whic store a string

#variable  is aname given to memory location


print(name)#printing of a name

age=23 #storing of value  23 in variable age
age2=age #the value of age is stored in age2
print(type(name))  #output :class string
print(type(age))  #output :class int
print(type(age2))  #output :class int


#datatype : integer,string, float , boolean, none


#string

name1="shivam"

name2='sk'

name3="""sk"""

print(name1,name2,name3)

#integer
age=23 #storing of value  23 in variable age
age2=age #the value of age is stored in age2
print(type(age))

#float

float=2.3#decimal value
print(type(float))


#Bollean
bool=True #a variable storing boolean value
print(type(bool))

#None
none=None #Variable storing nothing
print(type(none))

#python is a case sensetive

a=2
b=2
print(a+b)


#arthematic operator
a=5
b=6
sum=a+b
print(sum)

Devide=a/b
print(Devide) #output will be floating point number

mul=a*b 
print(mul)

Diffrence=a-b
print(Diffrence)\


modulo=a%b #here a<b so ooutput is 5
print(modulo)


#relational operator
num1= 5
num2=6
print(num1==num2)#output False

print(num1>=num2) #output False
print(num1<=num2) #output True

#Assigenemnt operator

my_marks=50 #assigining value
my_marks+=50 #assigining value by incrementing
my_marks -=50 #assigining value by decrement


#Logical operator

print(not False)
print(not True)

val1=True
val2=False
print(val1 and val2)
print(val1 or val2)


#Type conversion

"""
a,b=1,2.0


sum=a+b


"""
type1,type2=1,2.0


sum_type=type1+type2 #type conversion-->Automatic
print(sum_type ) #output=3.0 bcz float store more data than int


#typecasting

val3=1
val4="2"
val5=int(val4)
final_sum=val3 + val5
print(final_sum)


#input in python

input("Enter your name")

#by default input is taken as string

val6=int(input("enter the integer value"))
