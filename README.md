# slicing
#finding out max value using range
n = int(input())
a = list(map(int,input().split()))
m = 0
for i in range(n):
  if a[i] > m:
    m=a[i]
print(m) 

#without using range
n=int(input())
a=list(map(int,input().split()))
m=0
for i in a:
  if i>m:
    m=i
print(m)    

#finding out max value with index using range
n=int(input())
a=list(map(int,input().split()))
m=0
for i in range(n):
  if a[i]>m:
    m=a[i]
ind=a.index(m)
print(m,ind)


#max value with index without using range
n=int(input())
a=list(map(int,input().split()))
m=0
for i in a:
  if i>m:
    m=i
ind=a.index(m)
print(m,ind)



     
    
