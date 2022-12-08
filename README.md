# odd
all the odd num from list
def listnum(l1):
    a=len(l1)
    for i in range(a):
        if(l1[i]%2!=0):
            print(l1[i])
l=[1,2,3,4,5]
listnum(l)
