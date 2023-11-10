# Sum-
#To find the sum of all odd numbers up to 'n'
n=int(input("Enter number:"))
sum = 0
i =0
while i<= n:
    if i%2==1:
        print(i)
        sum+=i
    i+=1
print("Sum of oddnumbers = ",sum)
