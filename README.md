# CODSOFT 
def add(p, q)
return p+q
def sub(p, q) 
return p-q
def mul(p, q) 
return p*q
def div(p, q) 
return p/q
print("select the operation ") 
print(" 1. Addition") 
print(" 2. Substraction") 
print(" 3. Multiplication ") 
print(" 4. Division") 
ch= (input("Enter the choice ")) 
n1 = (input(" Enter the first number")) 
n2 = (input("Enter the second number")) 
if ch== '1':
print(n1"+"n2 "=", add(n1, n2)) 
elif ch=='2':
print(n1"-" n2"=", sub(n1, n2)) 
elif ch== '3':
print(n1"*"n2 "=", mul(n1, n2) 
elif ch=='4':
print(n1"/" n2 "=", div(n1, n2) 
else:
print (" Invalid choice ") 
