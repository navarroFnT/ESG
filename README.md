# ESG
Equação do Segundo Grau

import math 
print("Digite os coeficientes da equação dp 2° grau") 
a= int(input("a:")) 
b= int(input("b:")) 
c= int(input("c:")) 
delta=b**2-4*a*c 
x1= (-b + math.sqrt(delta)) / (2*a) 
x2= (-b - math.sqrt(delta)) / (2*a) 
print ("O delta da esquação é:", delta) 
print ("As raízes da esquação",x1, "e", x2) 
