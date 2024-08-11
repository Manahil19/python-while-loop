# python-while-loop
#1
limit = 5
count = 1

while(count <= limit):
    print("10 X ",count," = ", 10* count)
    count += 1            # count = count + 1

#2
limit = int(input("Enter Range of Table : "))
count = 1
print("Before Loop!")
while(count <= limit):
    print("5 X ",count," = ", 5 * count)
    count += 1            # count = count + 1
print("After Loop!")

#3
count = int(input("Enter Start of Table : "))
limit = int(input("Enter Range of Table : "))

print("Before Loop!")
while(count <= limit):
    print("5 X ",count," = ", 5 * count)
    count += 1            # count = count + 1
print("After Loop!")

#4
N = int(input("Enter your Number : "))
r1 = int(input("Enter r1 : "))
r2 = int(input("Enter r2 : "))

if(r1 > r2):
    temp = r1
    r1 = r2
    r2 = temp

print("Before Loop!")
while(r1 <= r2):
    print(N," X ",r1," = ", N * r1)
    r1 += 1            # count = count + 1
print("After Loop!")

#4
current_fee=50000
a=1
b=5
v=2
while a<=b:
    current_fee+=(current_fee*(v/100))
    a+=1
    v+=2
    print("Total fee %.2f"%current_fee)

#5
fact=1
a=1
num=int(input('enter a number : '))
while a<=num:
    fact=fact*a
    a+=1
    print('factorial of',num,"=",fact)

#6
fee=50000
a=1
b=5
v=2
while a<=b:
    fee+=fee*(v/100)
    a+=1
    v+=2
    print('Total fee %.2f'%fee

#7
fee=50000
a=1
b=5
v=2
while a<=b:
    fee+=fee*(v/100)
    a+=1
    v+=2
    print('total fee %.2f'%fee)

#8
fact=1
a=1
num=int(input("enter any number : "))
while a<=num:
    fact+=fact*a
    a+=1
    print("factorial of",num,"=",fact)
