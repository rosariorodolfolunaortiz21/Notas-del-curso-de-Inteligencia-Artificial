# Notas del Curso de Inteligencia Artificial

En este repositorio se subirán las notas correspondientes al curso de Inteligencia Artificial durante el semestre.

Alumno: Rosario Rodolfo Luna Ortiz

Inteligencia Artificial                                      13 01 26

[dibujo: esquema con caja Agente y flechas hacia PEAS]

Agente

Performance
Entorno
Actuadores
Sensores

P1, P2, ..., Pi, Pi+1

Estado S es la representación del entorno que está dado por un vector donde cada vector pertenece a un dominio independiente de forma:

S = {s1, s2, ..., sn}  s1 ∈ D1  s2 ∈ D2  ...  sn ∈ Dn

[dibujo: tabla con filas y columnas representando variables del estado]

 = { Ci, Cj, Ck, ..., im }

Representación de un estado único

ik = indicador si hay punto en la posición

C = i·k / m
k = i·m

fe ∈ {0,1}
ik ∈ {0,1}
k ∈ {0,1,...,m-1}

ve ∈ {0,1,...,n-1}

Mi espacio disponible son todas las combinaciones disponibles

La dimensionalidad:

S = 1 + n + m + 2^(n+m)         (n + m)

[dibujo: bloque con 3 columnas etiquetadas y objetos en la primera]

Otro ejemplo:

[dibujo: bloques en A, B, C]

-------------------------------------------------------------

Problema 1                                       Problema 2

[dibujo problema 1: A B C columnas con bloques apilados]
[dibujo problema 2: matrices de 3x3 y figuras a la derecha]

1)

S = [ i11 , i15 , i21 , i25 , ..., i31 , i35 ]

i a,b ∈ {0,1}

|S| = 2^15

Otra manera:

2)

S = { S1 , S2 , ..., S5 }

Si   S ∈ {A,B,C}

|S| = 3^5 = 243

3)

S = {E, O, L}

E = {0,1,2,3}
O = {0,1,2,3}
L = {D, I}
