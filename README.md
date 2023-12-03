num = int(input("Enter a number: "))
    
for i in range(2,num+1):
    for j in range(2,num+1):
        if i%j == 0:
            break
    if i == j:
        print(i,end=',')# Python-program-to-print-prime-numbers
Python program to print prime numbers from 1 to N using for loop
