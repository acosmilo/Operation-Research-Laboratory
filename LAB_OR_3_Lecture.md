# LAB 3 

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

1) Resolve the LP Model with ORtools
2) Compare the solution with graphical method and Excel Solver
3) Make a report about it. 

## Process

### 1) Model the problem of Linear Programation with Excel



### 2) Use the graphic method to solve the problem

- Se comienza graficando las inecuaciones de cada restricción. Graficar una inecuación consiste en primero graficar la recta de la ecuación y despues sombrear la región a la que la inecuación hace referencia. Consideren $x_1$ el eje x y $x_2$ el eje y.

https://www.desmos.com/calculator?lang=es


- Las diferentes inecuaciones se sombreran e intersecaran formando una región denominada. Región Factible. 
- Obtendremos las coordenadas de cada esquina de la región factible. ($x_1$, $x_2$)


- Una vez tenga todas las cordenadas de las esquinas evaluo sus valores en la FO: Z. La Z mayor es mi mayor ganancia (Debido a que maximizo), por lo que esas coordenadas es la Solución Optima del Problema.

Z(0, 4.5) =3(0)+2.5(4.5) =11.25
Z(1.5, 3) =3(1.5)+2.5(3) =12
Z(3, 0) =3(3)+2.5(0) =9

## Solucion.
Diariamente deben producirse 1.5 SEDANS y 3 Speed Cars, para maximizar los ingresos. Esta es la solucipon más óptima.

### 3) Report  

## Problem 2 (Video): Hacer Sanduches

Let's start with our sandwich business: the MIXTO and the Double Cheese. These consist of:

    MIXTO: 2 slices of bread, 1 slice of ham, 1 slice of cheese
    Double Cheese: 3 slices of bread, 4 slices of cheese,

We have limited inventory; daily we have:

    10 slices of bread
    12 slices of ham
    9 slices of cheese

We want to make a lot of money. How many sandwiches should we produce per day to maximize profits? If we earn per sandwich

    MIXTO $2
    CHEESE $2.1

### Activities

    1) Use ORTOOLS from Python to solve the problem and compare with  the graphic method 
    2) Make a Sensibility Analysis with Python
    2) Make a Report

### Solution (Video)

#### 1) Use Solver from Excel to solve the problem and compare with  the graphic method 
Parte I: https://youtu.be/NDIqUcJBVy4
#### 2) Make a Sensibility Analysis
Parte II:

Entregar un reporte en PDF que debe tener:

La caratula oficial (Si no pones tu nombre o no pones la caratula no vale este entregable)
La transcripción del problema incluyendo tablas o gráficas
La creación del modelo EXPANDIDO y GENERALIZADO con: Conjuntos, Función Objetivo, restricciones, etc.
La solución hecha en Excel usando Solver. Tomar capturas de pantalla del proceso de solución en Excel e incluir en el informe
Interpretar los resultados 

Subir a la carpeta LAB 2:
- Resolución enExcel: LAB_OR_2_Nombre_Apellido.xlsx
- Reporte en PDF: LAB_OR_2_Nombre_Apellido.xlsx

<img width="781" height="307" alt="imagen" src="https://github.com/user-attachments/assets/54e573af-9e20-4cae-a527-c3b17f433897" />
Fuente: Libro de Hiller

Rúbrica: Valor total 100: En cada uno de los siguientes apartados la nota se distribuye proporcionalmente en partes iguales, 
el profesor evaluara que tanto completó o no cada apartado y pondrá la nota. 
- Caratula
- Definir los conjuntos, parámetros y variables (si no esta hecho bien, tal como esta en el material, tiene cero)
- Modelo Expandido (si no esta hecho bien, tal como esta en el material, tiene cero)
- Modelo Generalizado (si no esta hecho bien, tal como esta en el material, tiene cero)
- Solucion por medio de Excel (si no esta hecho bien, tal como esta se hizo en la clase, usando regla calculando y dibujando la recta, verificando cual es la región que se pinta, claculando los puntos de intersección, tiene cero, no vale graficadoras ni saltarse los pasos)
- Conclusión escrita (cual es la solución optima tomando en cuenta unidades de las var decisión y las ganancias obtenidas, si no esta hecho bien es cero)


Si no estan subidos todos los documentos requeridos automáticamente es cero.
Si no esta tu nombre es cero
Si subiste la carpeta donde no era es cero
Si subiste por error otro archivo es cero
Si faltas sin una justificacipon válida es cero
