#program to find largest of three numbers
a=int(input("enter first number :"))
b=int(input("enter second  number :"))
c=int(input("enter third number:"))

if a>b and a>c:
   print("largest :",a)
elif b>c:
    print("largest:",b)
else:
        print("Largest:",c)
