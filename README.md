# desendingorder


11.Write a python program to print first n odd numbers in descending order.

n=int(input("Enter the Limit"))
if n%2==0:
    for i in range(n-1,0,-2):
        print(i)
    else:
        for i in range(n,0,-2):
            print(i)

Output:
Enter the Limit6
5
3
1
6
4
2
