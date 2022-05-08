# oddandeven-keys-in-dict
n=int(input("enter how many keys:"))
d={}
for i in range(1,n):
    k=int(input())
    if i%2==0:
        v='yes'
        d[k]=v
    else:
        v='no'
        d[k]=v
print(d)
