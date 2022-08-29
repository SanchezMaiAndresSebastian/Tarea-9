# Tarea-9
Circuitos RLC y resonancia - Filtros Pasivos

### 1. OBJETIVOS

**Principales**
- Análisis de circuitos RLC en serie-paralelo
- Analizar la operación de filtros pasabajas y pasaltas en RC y RL


**Específicos**

- Identificar cuáles son las características de un circuito con corriente alterna.
- Determinar los capacitores de un circuito en serie y en paralelo.
- Determinar las relaciones que existe entre las ondas sinusoidales y el campo de los números complejos.
- Distinguir las siguientes problemáticas que puedan ocurrir en la construcción de un circuito en serie y en paralelo.

### 2. MARCO TEORICO
![](data:image/png;base64,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)

![](https://www.researchgate.net/profile/Jaime-Gonzalez-Velasco/publication/325285644/figure/fig8/AS:629017501769735@1526980867264/Figura-116-Calculo-de-la-impedancia-total-de-un-circuito-formado-por-una-impedancia-en.png)

### 3. EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-01.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-02.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-03.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-04.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-05.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-06.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-07.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-08.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-09.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-10.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-11.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-12.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-13.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-14.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-15.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-16.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-17.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-18.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-19.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-20.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-21.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-22.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-23.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-24.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-25.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-26.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-27.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-28.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-29.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-10.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-11.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-12.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-13.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-14.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-15.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-16.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-17.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-18.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-19.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-20.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-21.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-22.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-23.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-24.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-25.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-26.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-27.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-28.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-29.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-30.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-31.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-32.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-33.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-34.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-35.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-36.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-37.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-38.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-39.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-40.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-41.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-42.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-43.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-44.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-45.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-46.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-47.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-48.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-49.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-50.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-51.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-52.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-53.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-54.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-55.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-56.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-57.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-58.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-59.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-50.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-51.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-52.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-53.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-54.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-55.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-56.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-57.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-58.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-59.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-60.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-61.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-62.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-63.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-64.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-65.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-66.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-67.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-68.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-69.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-70.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-71.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-72.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-73.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-74.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-75.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-76.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-77.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-78.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-79.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-80.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-81.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-82.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-83.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-84.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-85.png)
![](https://github.com/SanchezMaiAndresSebastian/Tarea-8/blob/main/Fotos/Tarea%208%20-%20Fund.%20de%20Circuitos%202022-86.png)



### 4. VIDEO

https://youtu.be/Y-3tUByS7xI

### 5. CONCLUSIONES

- Las características de la corriente alterna es que a medid que avanza el tiempo siempre está cavilando y una frecuencia y velocidad, por ende, esto se puede utilizar en funciones de onda.
- La Característica principal de un circuito en paralelo es de que tienen diferentes corrientes y el mismo voltaje en el nodo.
- La potencia en un circuito en serie es la suma de todas las potencias que existen en los resistores que acompañan a dicho circuito en serie.
- Dependiendo de la cantidad de corriente que se ingresas al capacitor esta ira bajando de manera controlada su corriente y voltaje.
### 6. BIBLIOGRAFÍA

- Dore, R. C., & Sobada, J. A. (2010). Introducción ti Electric Circuitos (8.a ed.). John Wiley & Sons Inc.
- Floyd, T. L. (2022). Principios De Circuitos Eléctricos C/Cd Rom (8.a ed.). PRENTICE HALL/PEARSON.v  
