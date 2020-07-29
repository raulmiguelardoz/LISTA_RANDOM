# LISTA_RANDOM
import random
lista=['Eduardo', 'Raquel', 'Roberto', 'Marines', 'Isabel']
dicc={}
ID=[]
for i  in range(1,len(lista)+1):
    ID.append(i)
i=0
while i<len(lista):
    x=random.choice(ID)
    dicc[lista[i]]=x
    ID.remove(x)
    i+=1
    
for i in dicc:
    print(i,dicc[i])
