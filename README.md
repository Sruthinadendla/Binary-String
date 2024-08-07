# Binary-String
def binaryString(n):
  a=1 
  b=1 
  i=1 
  while(i<n):
    temp=a+b
    b=a
    a=temp
    i+=1 
  return(a+b)%1000000007
n=int(input())
print(binaryString(n))
