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

#---------Todos os tipos de str--------

name = "luis"

print(len(name))

#len diz o número de caracteres da variável

print(name.find("i"))

#find diz o numero do caracter a começar do zero

print(name.capitalize())

#capitalize faz com que o primeiro caracter muda para maiúscula

print(name.upper())

#upper foz com que todos os caracteres fiquem em maiúsculas

name2 = "LUIS"
age = "12"

print(name2.lower())

#lower faz com que todos os caracteres maiúculos fiquem minúculos

print(name.isdigit())
#OU
print(age.isdigit())

#esdigit dirá se é True or False dependendo se for números ou palavaras
#Com números = True
#Com plavras = False

name5 = "Luis Oliveira"
name10 = "LuisOliveira"

print(name5.isalpha())
print(name10.isalpha())

#isalpha serve para ver se tem espaço ou não a variável
#Com espaço = False
#Sem espaço = True

print(name5.count("i"))

#count serve para contar o número de caracteres da letra que escolhermos

print(name5.replace("i", "a"))

#replace serve para substituir uma letra por outra

print(name*2)

# * + algum nº serve para multiplicar a variável
