# BubbleSort
My first Repository.
n=int(input("N:"))
l=[]
for i in range(n):
    l.append(int(input()))
for j in range(n-1):
    p=0
    while(p<n-j-1):
        if(l[p]>l[p+1]):
            temp=l[p]
            l[p]=l[p+1]
            l[p+1]=temp
        p+=1
print(l)
