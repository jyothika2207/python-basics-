# list with in a tuple
student=("jyothika",[22,45,90],['Math','Science','English'])
print(student[1])
print(student[2][1])
print(student[2][2])

# Simple tuple program
information=("Jyothika",19,'Enginner')
print(information[1])
print(information[-3])
print(len(information))
print(information*2)

#facorial of a given number
import math
def factorial(n):
    return(math.factorial(n))
    num=int(input("enter the number"))
    print(factorial(num))

#nested dictionary
information={
    'jyothika':{"salary":12000,"perks":30000},
    'sravya':{"salary":18000,"perks":50000},
}
print(information['sravya']['perks'])

#tuple keys in order to access a dictionary
location={
    (40.7128,-73.070):'New York',
    (34.0522,-119.2347):'Melbourne',
}
print(location[(40.7128,-73.070)])
