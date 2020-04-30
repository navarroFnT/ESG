# EQUAÇÃO DO SEGUNDO GRAU

def main() 
 import math 
 print("Digite os coeficientes da equação do 2° grau") 

def caluculo(x)
 a= int(input("a:")) 
 b= int(input("b:")) 
 c= int(input("c:")) 
 delta=b**2-4*a*c 
 x1= (-b + math.sqrt(delta)) / (2*a) 
 x2= (-b - math.sqrt(delta)) / (2*a) 
 print ("O delta da equação é:", delta) 
 print ("As raízes da equação",x1, "e", x2) 
