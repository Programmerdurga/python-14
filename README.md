# python-14
fuction-1
'''enter the value of a3
enter the value of b4
3 is less then 4'''
def relate(a,b):
 if a==b:
    return 0
 if a>b:
    return 1
 if a<b:
    return -1
a=int(input("enter the value of a"))
b=int(input("enter the value of b"))
res=relate(a,b)
if res==0:
    print(a, "is equal to", b)
if res==1:
    print(a, "is greater then",b)
if res==-1:
    print(a, "is less then", b)
