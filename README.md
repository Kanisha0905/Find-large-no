# Find-large-no
.n=int(input("Enter the Limit less than 99999999999"))
small=99999999999
for i in range(1,n+1):
     print("Enter ",i,end='')
     a=int(input("th number:"))
     if a<small:
         small=a
     print("Smallest no.is:",small)



Output:
Enter the Limit less than 999999999995
Enter  1th number:12
Smallest no.is: 12
Enter  2th number:3
Smallest no.is: 3
Enter  3th number:45
Smallest no.is: 3
Enter  4th number:2
Smallest no.is: 2
Enter  5th number:78
Smallest no.is: 2

