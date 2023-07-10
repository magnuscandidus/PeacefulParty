# PeacefulParty
# cook your dish here
t=int(input())
while t:
    a,b,c=map(int,input().split())
    if((a+c)>b):
        print(a+c)
    else:
        print(b)
    t-=1
