# day-13
a=int(input())
n=1
for i in range(1,a+1):         
    for j in range(1,i):
        n=n*j
    n=n*i
print(n)
