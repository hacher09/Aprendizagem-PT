#-----VARÁVEIS:-----

print("Hello world")

name = "beginning"
print("Im " + name)

#Com números pode ser string =str ou pode ser int dependendo das aspas
#Com aspas é str sem é int(int só pode ser numeros)
age1 = "21"
age2 = 21
#print(type(age1))

First_name = "Luis "
Last_name = "Oliveira "
Full_name = First_name + Last_name

print("My name is: " + (Full_name))
print("My age is: "+str(age2))
#print(type(Full_name))

#Não podemos ixibir mensgens como por exp: print(Last_name + age2)
#Porque se verificarmos as variáveis o tipo de dados delas são diferentes


height = 1.70
print("My height is: "+str(height)+"M")
#print(type(height))

#Neste caso temos uma variavel de tipo float
#É considerada flot porque tem números decimais
# ------Várias variáveis em uma linha de código:---
#name = "Luis"
#age = 12
#sexy = True

#É igual a:

name, age, sexy = "Luis", 12, True

print(name)
print(age)
print(sexy)

Comedor = Feliz = Brincalhão = True

print("Eu sou comedor: "+str(Comedor))
print("Eu sou feliz: "+str(Feliz))
print("Eu sou brincalhão: "+str(Brincalhão))
