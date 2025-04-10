Resolveremos un examen final de Algoritmos y Estructuras de Datos II, 
pero con un nivel de detalle mayor, aplicando principios de modularidad de Bertrand Meyer, calidad y principios SOLID.



Simulación Final Algoritmos y Estructuras de Datos II
Instituto Superior de Formación Técnica N.o 151
Carrera: Analista de Sistemas

Algoritmos y Estructuras de Datos II.
1 Año. FINAL

Una empresa nos convoca para armar una APP que controle el clima de un datacenter. La misma deberá
tener registro (actual e histórico) de: temperatura, humedad y permitiendo controlar el “Clima” a través de
una API de terceros (MS-Forecast) que se invocan desde la APP. La APP será por consola a efectos del final.
La APP MS-Forecast posee las siguientes interfaces:
1. Up_Temp( int X)
2. Down_Temp( int X)
3. Up_Humity( int X)
4. Down_Humity( int X)
5. Read_Temp
6. Read_Humity
EL componente MS-Forecast se invoca directamente (se sugiere construir un MOCK para simularlo)
Desarrollo del Final:
1.Marco Teórico:
Sobre el problema presentado relacionar:
1. Relacionar UML, S.O.L.I.D. GRASP, en el marco del diseño de software.
2. Explicar el polimorfismo basado en interfaces

2. Marco Practico Modelado:
Sobre el problema presentado realizar:
1. Realizar 2 casos de uso.
2. Realizar el diagrama de clases.
3. Realizar 1 diagrama de secuencia.
3.Marco Practico Software
Sobre el problema presentado realizar:
1. Desarrollar un APP que contenga las clases anteriores que además permita guardar históricos de
temperatura y humedad. Además enviar alertas por mail.
