# Print-the-patterns-
I) n=int(input("Enter the limit:"))
for i in range(1,n+1):
    for j in range(1,i+1):
        print("*",end='')
        print(" ")

Output
Enter the limit:1
*
(ii)n=int(input("Enter the limit:"))
for i in range(1,n+1):
    for k in range(n-i,0,-1):
        print('',end='')
    for j in range(1,i+1):
        print("*",end='')
    print(" ")

Output
Enter the limit:3
*
**
