#print the sum of first  n natural numbers n=10, output:55
sum=0
i=1
n= int (input ("enter the value of n:"))
while i<=n:
    sum+=i
    i+=1
print("total:",sum)
