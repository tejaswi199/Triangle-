#Approach 1
a,b,c=map(int,input().split())
if(a<(b+c)):
  if(b<(c+a)):
    if(c<(b+a)):
           print("Yes ")
    else:
        print("No")
  else:
    print("No")
else:
  print("No ")
#Approach-2
a,b,c=map(int,input().split())
if a<(b+c) and b<(a+c) and c<(a+b):
  print("Yes")
else:
  print("No")
