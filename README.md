from array import *
arr = array('i',[])
n = int(input("enter the length of array"))
for i in range(n):
    x = int(input("enter the next number"))
    arr.append(x)

print(arr)

val = int(input("enter the search value"))

k = 0
for e in arr:
    if e == val:
        print(k)
k += 1
