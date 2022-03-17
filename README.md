# Ass-2-17-03-2022
To check validity of password 

s=input("enter password")
l1=list(s)
l=0
u=0
d=0
s=0
for i in l1:
    if(i.islower()>0):
        l=l+1
    elif(i.isupper()>0):
        u=u+1
    elif(i.isdigit()>0):
        d=d+1
    else:
        s=s+1
print("valid")

o/p:
enter passwordsam12@
valid
