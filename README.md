# 24-2-22-assignment1
x=input()
l=x.split()
n=len(l)
o=[]
e=[]
for i in range(n):
    j=i+1
    if j%2==0:
        e.append(l[i])
    else:
        o.append(l[i])
       
print(o,'  ',e)

out put
