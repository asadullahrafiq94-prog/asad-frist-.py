name = input("Enter your name: ")
print("Hello,", name)

print(input("please you enter your age:"))
print(input("please enter yor phone number:"))
print(input("please enter  address:"))
print(input("pleae enter your email:"))
print(input("please enter your gender:"))
print(input("please enter your date of birth:"))
print(input("please enter your nationality:"))
print(input("please enter your marital status:"))
#sum=>a,b\x,y =>sum
a=int(input("Enter a:"))
b=int(input("Enter b:"))
str = a+b
print("str:",str)



a=int(input ("Enter your number x"))
b=int(input ("Enter your number y"))
str = a/b
print("str:",str)



a=int(input ("Enter your number x"))
b=int(input ("Enter your number y"))
str = a*b
print("str:",str)


name="asad"
#string opration
print (name.upper())
print(name.lower())
print(f"{name}")


name=("asadullah rafiq")
print(name.find(" rafiq"))
print(name.replace("asadullah", "rafiq"))
print(name.split(" "))
print(name.index("asadullah"))

student=("aslam")
print("lam" in student)
print("asl"in student)
print("ar"in student)

#assignment opprators
x=14
print(x)
x=20
x+=30
print(x)
x-=30
print(x)

#algorithms_opratilns
 
print(14+14)#addition
print(13-13)#subtraction
print(12*12)#multiplication
print(12/12)#division
print(12%12)#modulo
print(12**12)#exponentiation
print(12//12)#integer division
print(12>13)#comparison

#oprators precedence
asd=10+12*2
print(asd)
asd=(10+12)*2
print(asd) 

#calclautor

from http.client import LOOP_DETECTED
from re import X
x=print(input("Enter your number:"))
y=print(input("Enter your number:"))
op=input ("Enter your opperator)(+,*,-,/,%,**,//):")
if op== '+':
    print(x + y)
elif op== '*':
    print(x * y)
elif op== '-':
    print(x - y)
elif op== '/':
    print(x / y)
elif op=='%':
    print(x % y)
elif op=='**':
    print(x ** y)
elif op=='//':
    print(x // y)
else:    
     print("invalid operator")   

 #logical operators
print(not  4560<3041)
print(not  4560>3041)
print(29>30 or 40<30)
print(30>15 or 30<10)
print(29>30 or 30>410)
print(40>32 or 50<32)
print(40>32 and 50<32)
print(30>15 and 30<100)
print(30>120 and 120>122)


#conditional statements


age=int(input("Enter your age"))
if age>= 18:
    name=(input("Enter your name:"))
    print("Hello,", name)
    print(input("Eter your father name:"))
    print(input("Enter your phone number:"))
    print(input("Enter your Email id:"))
    print ("give your ID card and draiving laessans")
    print("go back your jurney")
    print("thank you brothar")
elif age<=18:
    print("your age less then 18 years")
    print("you can't jurney")
    
print("end of cord")   
#for loop
nums=range(1,101)
for i in nums:
    print(i)
print("end of loop")    

m=range(1,1001)
for i in m:
    print(i)
print("end of loop")
#whele loop
i=1000
while i>=1:
    print(i)
    i-=1
    #for loop shortcut typeS
for i in range(1,5001):
    print(i)

for i in range(1, 20):
    print(i) if i % 2== 0 else print ("not divisible by 2")
    
for f in range(1, 1001):
        if f % 3==0:
          print(f)
for h in range(2 ,1001 , 2):
     print(h)

# break and continue statements

     for f in range(2, 50):
            if(f== 20):
                continue
            if(f% 2==0):
              print(f)
              for f in range(1, 1001):
                    if(f==40 or f==50):
                          break
                    if(f% 5==0):
                          print(f)

#list and function that parform in this list
# list in for LOOP
                          
num = [12, 13, 14, 15, 16, 17, 18, 19, 20]
name = ["ali", "aslam", "ahmad", "rafiq", "asadullah", "zan", "mubeen", "shahin", "shahzab", "shabaz"]

for student, score in zip(name, num):
    print(student, ":", score)

num2 = [83, 18, 84, 84, 32, 38, 23, 35]
aas2 = ["ali", "aslam", "ahmad", "rafiq", "asadullah", "zan", "mubeen", "shahin", "shahzab", "shabaz"]

print("\nUsing num2 and aas2:")
for student, score in zip(aas2, num2):
    print(student, ":", score)


    nums3=[10,9,8,7,6,5,4,3,2]
    ch=["asad", "aslam","jhanzab","murtza","ali","alyas",]
    for student, score in zip(nums3, ch):
        print(student, ":" , ch)

     
num = [12, 13, 14, 15, 16, 17, 18, 19, 20]
name = ["ali", "aslam", "ahmad", "rafiq", "asadullah", "zan", "mubeen", "shahin", "shahzab", "shabaz"]
num.insert(5,50)
print(num)
num[:3]
num[:-3]#etc



nums3=[10,9,8,7,6,5,4,3,2]
print(len(nums3))
nums3.clear()
print(nums3)

#tuple   

nums=(11,23,45,69,73,35,67,89)
print(type(nums))
print(nums)
print(nums.index(73))



#set in python
nums={11,23,45,69,73,35,67,89}
print(type(nums))
print(len(nums))
