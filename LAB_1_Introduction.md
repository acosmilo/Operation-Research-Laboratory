# LAB 1 Introduction


## Problem 1 TOYCARS
First, in a groups of 3 people. Imagine you are going to sale 2 types of toycars: SEDAN and Speed Car. 
And also the toys are made it with:
- SEDAN: 1X chasis (EW13), 4X blue lego blocks 2x6 (RE54), 2X red lego blocks 2x2 (RE52).
- Speed Car:  1X chasis (EW13), 2X blue lego blocks 2x6 (RE54), 2X red lego blocks 2x2 (RE52).

Our problem is we had the constrain of inventory per day:
- 10 EW13
- 12 RE54
- 9 RE52


Our boss want to know how many SEDAN and Speed Cars we need to produce per day. If we want to increase our  earninggs to the maximum possible value
we sale them with a price of:
- SEDAN: $3
- Speed Car: $2,5

## Activities

1) Empirically finds the best solution
2) Model the problem of Linear Programation
3) Use the graphic method to solve the problem

## Model the problem of Linear Programation

See LAB_1_Introduction.pdf

## Use the graphic method to solve the problem

- Se comienza graficando las inecuaciones de cada restricción. Graficar una inecuación consiste en primero graficar la recta de la ecuación y despues sombrear la región a la que la inecuación hace referencia. Consideren $x_1$ el eje x y $x_2$ el eje y.

https://www.desmos.com/calculator?lang=es


- Las diferentes inecuaciones se sombreran e intersecaran formando una región denominada. Región Factible. 
- Obtendremos las coordenadas de cada esquina de la región factible. ($x_1$, $x_2$)

<img width="1067" height="565" alt="imagen" src="https://github.com/user-attachments/assets/cc9e9c5c-2bb4-4807-b6a9-e0156aa315c4" />

- Una vez tenga todas las cordenadas de las esquinas evaluo sus valores en la FO: Z. La Z mayor es mi mayor ganancia (Debido a que maximizo), por lo que esas coordenadas es la Solución Optima del Problema.

Z(0, 4.5) =3(0)+2.5(4.5) =11.25
Z(1.5, 3) =3(1.5)+2.5(3) =12
Z(3, 0) =3(3)+2.5(0) =9

## Solucion.
Diariamente deben producirse 1.5 SEDANS y 3 Speed Cars, para maximizar los ingresos. Esta es la solucipon más óptima.

## Entregable "Punto Extra: Por venir el primer dia"
Individual.
A mano en hojas.
Al final toman foto y suben al D2L, carpeta "Punto Extra: Por venir el primer dia"
Pongan su nombre.
Resolver el siguiente ejercicio.

Vamos a empezar con nuestro emprendimiento de sanduches: MIXTO y cuadruple Queso. 
Los cuales se conforman de 
- MIXTO Tocino : 2x rebanadas, 1x jamon, 1x queso
- Doble Queso:  3x rebanadas,  4x queso, 

Tenemos una limitación en el inventario, diariamente disponemos de:
- 10 rebanadas
- 12 jamón
- 9 queso

Queremos ganar mucha plata, ¿Cuántos sanduches debemos producir al dia para maximizar las ganancias? Si por sanduche ganamos 
- MIXTO $2
- QUESO $2.1


Rúbrica: Valido por un punto extra al proyecto: Bien 1 Mal 0
- Si no esta hecho a mano es cero
- Definir los conjuntos, parámetros y variables (si no esta hecho bien, tal como esta en el material, tiene cero)
- Modelo Expandido (si no esta hecho bien, tal como esta en el material, tiene cero)
- Modelo Generalizado (si no esta hecho bien, tal como esta en el material, tiene cero)
- Solucion por medio del método gráfico hecho a mano (si no esta hecho bien, tal como esta se hizo en la clase, usando regla calculando y dibujando la recta, verificando cual es la región que se pinta, claculando los puntos de intersección, tiene cero, no vale graficadoras ni saltarse los pasos)
- Conclusión escrita (cual es la solución optima tomando en cuenta unidades de las var decisión y las ganancias obtenidas, si no esta hecho bien es cero)









