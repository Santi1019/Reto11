# Reto11

1. Desarrolle un programa que permita realizar la suma/resta de matrices. El programa debe validar las condiciones necesarias para ejecutar la operación.

Desarrollo
```
A = [[1,2,3],[2,3,4],[5,6,7]]

print("La matriz A es =")
for i in range(len(A)):
    for j in range(len(A)):
        pass
    print(A[i])

     

B = [[12,13,14],[15,16,17],[18,19,20]]  
print("La matriz B es =")      

for n in range(len(B)):
    for m in range ( len(B)):
        pass
    print(B[n])    


    

if len(A)==len(B) and len(A[j])==len(B[m]):
    C = []
    filaas_ = []

    print("La suma de matrices es =")
    for x in range(3):
        filaas_=[]
        for z in range(3):
            numero_nuevo = (A[x][z])+(B[x][z])
            filaas_.append(numero_nuevo)   
        C.append(filaas_)
    for i in range(len(C)):
        for j in range(len(C)):
            pass
        print(C[i])

A = [[1,2,3],[2,3,4],[5,6,7]]

print("La matriz A es =")
for i in range(len(A)):
    for j in range(len(A)):
        pass
    print(A[i])

     

B = [[12,13,14],[15,16,17],[18,19,20]]  
print("La matriz B es =")      

for n in range(len(B)):
    for m in range ( len(B)):
        pass
    print(B[n])    


    

if len(A)==len(B) and len(A[j])==len(B[m]):
    C = []
    filaas_ = []

    print("La resta de matrices es =")
    for x in range(3):
        filaas_=[]
        for z in range(3):
            numero_nuevo = (A[x][z])-(B[x][z])
            filaas_.append(numero_nuevo)   
        C.append(filaas_)
    for i in range(len(C)):
        for j in range(len(C)):
            pass
        
        print(C[i])
```
   

2. Desarrolle un programa que permita realizar el producto de matrices. El programa debe validar las condiciones necesarias para ejecutar la operación.
```

A = [[1,2,3],[4,5,6],[7,8,9]]

B = [[10,11,12],[13,14,15],[16,17,18]]

print("La matriz A es =")
for i in range(len(A)):
    for j in range(len(A)):
        pass
    print(A[i])



print("La matriz B es =")
for n in range(len(B)):
    for m in range(len(B)):
        pass
    print(B[n])

if len(A[j])==len(B[n]): #Debajo de esto haré todo lo demás, utilizando una variable local
    print("El producto de matrices es la matriz =")
    C = [[0 for i in range(len(A))] for i in range(len(A))]
    filas = []
     #Codigo finalizado después de ir a tutoría
    for w in range(len(C)): #Por cada fila del producto de matrices 
        for x in range(len(A[i])): #Que cada fila de A recorra las tres columnas de B
            for y in range(len(B[m])):
                C[w][y] += A[w][x] * B[x][y] 
    print(C)   
```
3. Desarrolle un programa que permita obtener la matriz transpuesta de una matriz ingresada. El programa debe validar las condiciones necesarias para ejecutar la operación.
```
A = [[1,2,3],[4,5,6],[7,8,9]]   
print("La matriz A es =")
for i in range(len(A)):
    for j in range(len(A[i])):
        pass

    print(A[i])





def matriz_transpuesta(n):
    transpuesta = [[0 for j in range(len(A))] for i in range(len(A))]
    for i in range(len(A)):
        for j in range(len(A)):
            transpuesta[i][j] = A[j][i]
    print(transpuesta)
    
if __name__ == "__main__":
    
    print("La matriz A transpuesta es =")
    a =int
    print(matriz_transpuesta(a))
```
4. Desarrollar un programa que sume los elementos de una columna dada de una matriz.
```
A = [[1,2,3],[4,5,6],[7,8,9]]
print("La matriz A es =")
for i in range(len(A)):
    for j in range(len(A[i])):
        pass
    print(A[i])




def suma_de_columna(n):
    suma:int=0
    for i in range(n-1,n): #Dentro del rango irá la columna que quiere sumar, siendo solo una iteración para que se sume solo una columna
        for j in range(len(A)):
            suma+=(A[j][i])
    return(suma)       


if __name__ == "__main__":
    n = int(input("¿Que columna quiere sumar?(Ingrese el numero): "))
    print(suma_de_columna(n))
```

5. Desarrollar un programa que sume los elementos de una fila dada de una matriz.
```
A = [[1,2,3],[4,5,6],[7,8,9]]
print("La matriz A es =")
for i in range(len(A)):
    for j in range(len(A[i])):
        pass
    print(A[i])


n = int(input("¿Que fila quiere sumar?(Ingrese el numero)"))
suma:int=0
for i in range(n-1,n):
    for j in range(len(A)):
        suma+=(A[i][j])
print(suma)
```
