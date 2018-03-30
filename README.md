# MULTIPLICATION-OF-DICTIONARY-VALUES
# we have to find the multiplication of the values in a dictionary for this first take input of dictionary from the user by using for loop ,and then initialize the variable with 1 and the again use for loop to find the product of values 
dict={}
n=int(input("enter the no. of key-values pair in the dictionary"))
for i in range(n):
    k=input("enter the key")
    v=int(input("enter its value"))
    dict.update({k:v})
# initilize the variable to 1
product=1
for j in dict.values():
    product*=j
print("the product is ",product)    
