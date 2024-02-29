# max-of-odd-numbers
# max of odd numbers
# approach-1
n=int(input())
a=list(map(int,input().split()))
r=0
for i in a: 
  if i%2!=0 and i>r:
    r=i
print(r)

# approach-2
n=int(input())
a=list(map(int,input().split()))
r=[]
for i in a: 
  if i%2!=0:
    r.append(i)
print(max(r))
