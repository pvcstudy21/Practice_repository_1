# Practice_repository_1


# 1. Write the code to find the lengh of string without using lengh function

s = "prathamesh"

count = 0
for i in s:
    count = count+1

print(count)

# 2. write a function to find the number is prime or not

def even_or_odd(n):
    if n%2 == 0:
        print("Even Number")
    else:
        print("Odd Number")


even_or_odd(5)
Odd Number

# Write a function to find the number is prime number or not 

def prime_or_not(n):
    for i in range(2,n):
        if n%i != 0:
            print("prime")
            break
        else:
            print("not prime)
            break


prime_or_not(5)
prime
