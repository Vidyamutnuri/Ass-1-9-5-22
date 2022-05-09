# Ass-1-9-5-22
Assignment-1
n=int(input())
d={}
for i in range (n):
    x=input().split()
    d[x[0]]=x[1]
while "TRUE":
    try:
        NAME=input()
        if NAME in d:
           print(d[NAME])
        else:
             print("not it found")
 except:
    break
