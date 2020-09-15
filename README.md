# JUST_THAT
print("""SELECT FROM THE LIST,WRITE NUMBER\n1). ADDITION
2). SUBTRACTION
3). MULTIPLICATION
4). DIVISION""")

print("enter your choice: ")
choice = int(input())
''' 45*3=555
    56+9=77
    56/6=44'''
print("enter the first number: ")
a = int(input())
print("enter last number")
b = int(input())
'''making the variable'''
x = 555
y = 77
z = 44
if choice == 1:
    if a == 56 and b == 9:
        print(y)
    else:
        print(a+b)
elif choice == 2:
    print(a-b)
elif choice == 3:
    if a == 45 and b == 3:
        print(x)
    else:
        print(a*b)
elif choice == 4:
    if a == 56 and b == 6:
        print(z)
    else:
        print(a/b)
else:
    print("WRONG INPUT!!!!!")
''' *** CODE ENDED *** '''
