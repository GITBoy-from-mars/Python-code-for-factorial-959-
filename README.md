# Python-code-for-factorial-959-
By using this code you will able to generate factorial of desired number

# Creating a function for factorial limit 959

def facto(n):
  if(n==0 or n==1):
    return 1
  else:
    return n* facto(n-1)
print(facto(int(input("enter a number for factorial: "))))
