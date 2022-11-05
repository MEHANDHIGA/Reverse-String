def reverse(s): 
    str = ""
    for i in s:
       str = i + str
    return str
s = "LetsUpgrade"
print("The original string is : ", end="")
print(s) 
print("The reversed string is : ", end="") 
print(reverse(s)) 

Output:
   The original string is : LetsUpgrade
   The reversed string is : edargpUsetL
