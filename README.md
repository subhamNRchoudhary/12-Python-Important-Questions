12 Python Important Questions

1. Reverse a Number

#easy way/method

n = 12345
a = int(str(n)[::-1])
print(a)

#we used (slicing)

def a(n):
    b = 0
    while n > 0: # Continue the loop as long as n is greater than 0
        digit = n%10 # Get the last digit of n by taking the remainder when n is divided by 10
        b = b * 10 + digit # Shift the digits of reversed_num left and add the new digit
        n = n // 10  # Remove the last digit from n by performing integer division by 10
    return b

print(a(123456789))

2. Find Common Letters from Two Words

#Two different method

a = input("enter 1st word:")
b = input("enter 2nd word:")
common = set(a) & set(b)
print("Letter : ",common)


a = "apple"
b = "sample"
common = set(a) & set(b)
print(common)
