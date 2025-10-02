# Teoría de la Computación 2025

Este es un curso introductorio a la teoría de la computación, la cual se ocupa de determinar cuáles problemas pueden ser resueltos computacionalmente y con qué eficiencia, así como de entender el límite entre los problemas computables y los no-computables, y clasificarlos de acuerdo a su simpleza o dificultad.  

El curso inicia con el estudio de distintos modelos de cómputo, como los autómatas finitos (que son los más sencillos), y sus diferentes tipos y aplicaciones; las máquinas de Turing (que son las computadoras usuales de hoy en día) y las computadoras cuánticas (cuyo funcionamiento no es digital). Una vez formulado un modelo de computación, nos interesa conocer la cantidad de recursos computacionales que es necesario utilizar para resolver un problema. El primero de estos recursos es el tiempo: cuántos pasos o cuántas acciones debemos realizar para resolver el problema. También son importantes el espacio ocupado, la necesidad de utilizar una fuente de números aleatorios, la posibilidad de resolver subproblemas en paralelo, entre otros.

La formalización de un modelo computacional como objeto matemático permite expresar de manera precisa preguntas sobre problemas o algoritmos. En particular, si L es un problema. ¿Puede L ser resuelto por un algoritmo? ¿Puede ser L resuelto de manera eficiente? ¿Cómo podemos construir un algoritmo eficiente para L? ¿Es L un problema para el cual no existe un algoritmo que lo resuelva? Contestaremos a algunas de estas preguntas, mientras que otras se verán en los cursos de Lógica Matemática y en Análisis de Algoritmos.


# Prerrequisitos

Se recomienda que los estudiantes antes del curso estén habituados con los siguientes temas:
* Álgebra lineal (matricial).
* Matemática discreta (conteo, permutaciones, divisibilidad, congruencias).
* Grafos (representaciones, propiedades, algoritmos).
* Cálculo (funciones, límites, derivadas).
* Estructuras y algoritmos (pilas y colas, árboles, grafos).

Bastará con haber cursado una materia de cálculo y una de mátemática discreta. En el caso de programación, conviene conocer muy bien los temas de estructuas de datos y algoritmos.

El curso tiene una carga fuerte en el tema de matemática y estructuras abstractas. Cuando sea conveniente, dedicaremos una parte del curso a cubrir algunos prerrequisitos necesarios en los temas.


# Programa del curso
<div id='id-programa'/>

[Programa del curso](programa/Programa-tc2025.pdf){:target="_blank"}


### Horario
<div id='id-horario'/>

* Lunes de 17:20 a 19:45 CIT-414, y Miércoles de 19:00 a 20:35 CIT-414.

### Office Hours
<div id='id-office'/>

* Martes o jueves, 19:00 a 19:45.


# Material del curso
<div id='id-material'/>

**No.**  | **Fecha**    | **Tópicos**                                                               | **Recursos**
-------- | ------------ | ------------------------------------------------------------------------- |  ---------------
01       | 02.07.2025   | Introducción al curso. Aspectos generales de la teoría de la computación. <br/> [Aula 01](aulas/Aula01.pdf){:target="_blank"} | Hopcroft, Sección 1.1   
02       | 07.07.2025   | Autómatas finitos deterministas (AFD). Función de transición. <br/> [Aula 02a](aulas/Aula02a.pdf){:target="_blank"} [Aula 02b](aulas/Aula02b.pdf){:target="_blank"} | Hopcroft, Secciones 2.1, 2.2 
03       | 09.07.2025   | Expresiones regulares o *regexp*. <br/> [Aula 03](aulas/Aula03.pdf){:target="_blank"} | Hopcroft, Sección 3.1
03       | 09.07.2025   | Árboles sintácticos de *regexp*. Notación infix, prefix y postfix. <br/> [Aula 04a](aulas/Aula04a.pdf){:target="_blank"} | Hopcroft, Sección 3.1
L1       | 14.07.2025   | Lab 01. <br/> | [Lab 01](labs/lab01.pdf){:target="_blank"} <br/> **Entrega: 21 de julio** 
04       | 16.07.2025   | Función de transición extendida. Configuraciones y derivaciones. <br/>  [Aula 04b](aulas/Aula04b.pdf){:target="_blank"} | Hopcroft, Sección 2.2 
05       | 21.07.2025   | Autómatas finitos no deterministas (AFN). <br/>  [Aula 05](aulas/Aula05.pdf){:target="_blank"} | Hopcroft, Sección 2.3  
06       | 21.07.2025   | Conversión de AFN a AFD: Construcción de subconjuntos.	| Hopcroft-Ullman, Sección 2.5 
07       | 23.07.2025   | Épsilon-transiciones. Conversión de ε-AFN a AFD.	| Hopcroft-Ullman, Sección 2.5  
L2       | 28.07.2025   | Lab 02. <br/> | [Lab 02](labs/lab02.pdf){:target="_blank"} <br/> **Entrega: 4 de agosto** 
08       | 28.07.2025   | Conversión de regexp a AFN: Algoritmo de Thompson.  [Aula 06a](aulas/Aula06a.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 3.2  
09       | 30.07.2025   | Conversión de regexp a AFN: Método de Glushkov.  [Aula 06b](aulas/Aula06b.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 3.2  
10       | 30.07.2025   | Conversión de AFN a regexp: Algoritmo de reducción.  [Aula 07a](aulas/Aula07a.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 3.2  
11       | 04.08.2025   | Conversión de AFN a regexp: Método de Arden.  [Aula 07b](aulas/Aula07b.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 3.4 
L3       | 04.08.2025   | Lab 03. <br/> | [Lab 03](labs/lab03.pdf){:target="_blank"} <br/> **Entrega: 11 de agosto** 
12       | 06.08.2025   | Propiedades de cerradura. Producto de autómatas.  [Aula 08](aulas/Aula08.pdf){:target="_blank"}  | Hopcroft-Ullman, Sección 4.2
13       | 11.08.2025   | Propiedades de decisión. <br/> [Aula 09](aulas/Aula09.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 4.3
14       | 13.08.2025   | Equivalencia y minimización de autómatas. <br/> [Aula 10](aulas/Aula10.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 4.4
L4       | 18.08.2025   | Lab 04. <br/> | [Lab 04](labs/lab04.pdf){:target="_blank"} <br/> **Entrega: 25 de agosto** 
15       | 20.08.2025   | *Pumping Lemma* para lenguajes regulares. Ejemplos de lenguajes no regulares. [Aula 11](aulas/Aula11.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 4.1 <br/> [*Pumping Lemma* for RL](https://en.wikipedia.org/wiki/Pumping_lemma_for_regular_languages){:target="_blank"}
16       | 20.08.2025   | Gramáticas libres de contexto (CFG). Notación Backus-Naur.  [Aula 12](aulas/Aula12.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 5.1  
17       | 27.08.2025   | Ejemplos de CFGs. Comentarios sobre gramáticas sensibles al contexto. | Hopcroft-Ullman, Sección 5.2  
18       | 01.09.2025   | *Parsing trees*. Derivaciones a la izquierda y a la derecha. [Aula 13](aulas/Aula13.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 5.3 
19       | 01.09.2025   | Ambigüedad. Remoción de la ambigüedad. <br/> [Aula 14](aulas/Aula14.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 5.4 
20       | 03.09.2025   | Algoritmo de simplificación de gramáticas CFG. <br/> [Aula 15](aulas/Aula15.pdf){:target="_blank"} | [Ejemplo 1](labs/Ejemplo1_Reduccion.txt){:target="_blank"}  [Ejemplo 2](labs/Ejemplo2_Reduccion.txt){:target="_blank"} 
21       | 08.09.2025   | Revisión del primer proyecto. <br/> | 
22       | 10.09.2025   | Formas normales. Forma Normal de Chomsky <br/> [Aula 16](aulas/Aula16.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 5.3 
L5       | 10.09.2025   | Lab 05. <br/> | [Lab 05](labs/lab05.pdf){:target="_blank"} <br/> **Entrega: 24 de septiembre**  
23       | 24.09.2025   | Autómatas de pila (PDA). <br/> [Aula 17](aulas/Aula17.pdf){:target="_blank"} [Aula 18](aulas/Aula18.pdf){:target="_blank"} | Hopcroft-Ullman, Secciones 6.1 y 6.2  
24       | 29.09.2025   | Ejemplos. Equivalencia entre PDA y CFG. <br/> [Aula 19](aulas/Aula19.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 6.3 
L6       | 29.09.2025   | Lab 06. <br/> | [Lab 06](labs/lab06.pdf){:target="_blank"} <br/> **Entrega: 6 de octubre**  
25       | 01.09.2025   | *Pumping Lemma* para lenguajes libres de contexto <br/> [Aula 20](aulas/Aula20.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 6.3 

 
# Lecturas complementarias
### (Autores: T. Gálvez, B. Pojoy, P. Mejía y A. Reyes-Figueroa, 2022).
<div id='id-notas'/>

**No.**  | **Fecha**    | **Tópicos**                                             | **Recursos**
-------- | ------------ | ------------------------------------------------------- |  -------------------------------------
01       | 23.07.2025   | Lectura 1 - Expresiones regulares y AFNs.               | [Lectura 1](lectures/Lectura01.pdf){:target="_blank"}
02       | 23.07.2025   | Lectura 2 - Conversión de AFNs as AFDs.                 | [Lectura 2](lectures/Lectura02.pdf){:target="_blank"}
03       | 20.08.2025   | Lectura 3 - Algoritmo de minimización de AFDs.          | [Lectura 3](lectures/Lectura03.pdf){:target="_blank"}

  
# Proyectos
<div id='id-proyectos'/>

En el curso se desarrollarán tres proyectos, los cuales se indicarán más adelante.

## Primer Proyecto 

**No.**  | **Fecha**    | **Tópicos**                                             | **Recursos**
-------- | ------------ | ------------------------------------------------------- |  ---------------------
1        | 12.08.2025   | Proyecto 1 - Algoritmos sobre AFDs, AFNs y *regexp*.    | [Proyecto 1](proyectos/Proyecto1.pdf){:target="_blank"} <br/> **Fecha de Entrega: 08-12 septiembre.**
2        | 08.09.2025   | Presentación y revisión del proyecto.
3        | 12.09.2025   | Entrega del reporte final.


## Segundo Proyecto 

**No.**  | **Fecha**    | **Tópicos**                                                     | **Recursos**
-------- | ------------ | --------------------------------------------------------------- |  ---------------------
1        | 10.09.2025   | Proyecto 2 - Algoritmo CYK para gramáticas.                     | [Proyecto 2](proyectos/Proyecto2.pdf){:target="_blank"} <br/> **Fecha de Entrega: 22 de octubre.**
2        | 22.10.2025   | Presentación y revisión del proyecto.
3        | 24.10.2025   | Entrega del reporte final. 


# Referencias
<div id='id-ref'/> 

### Textos:

* [J. Hopcroft, R. Motwani, J. Ullman (2006). *Automata Theory, Languages and Computation*.](https://libgen.li/ads.php?md5=4e0316bcd5fc0a7398c037ecb77bf8e4){:target="_blank"}

* [J. Hopcroft, R. Motwani, J. Ullman (2007). *Teoría de autómatas, lenguajes y computación*.](libros/Hopcroft_Ullman.pdf){:target="_blank"}

### Referencias adicionales:

* [H. Lewis, C. Papadimitriou (1998). *Elements of the Theory of Computation*.](https://libgen.li/ads.php?md5=586beb94a1648cf624f74496477e92db){:target="_blank"}

* [J. G. Brookshear (1988). *Theory of Computation: Formal Languages, Automata, and Complexity*.](https://libgen.li/ads.php?md5=800ed3e6b91d0620db1f9e8574dcab04){:target="_blank"}

* [J. G. Brookshear (1993). *Teoría de la Computación, Lenguajes Formales, Autómatas y Complejidad*.](https://libgen.li/ads.php?md5=068cef10821208719e2a4d22f61f622c){:target="_blank"}

* [R. de Castro Korgi (2004). *Teoría de la Computación, Lenguajes Autómatas, Gramáticas*.](https://libgen.li/ads.php?md5=60501ae7549bf7b67bb11709240ce5b7){:target="_blank"}

* [E. Gaudioso Vásquez *et al.* (2017). *Introducción a la Teoría de Autómatas, Gramáticas y Lenguajes*.](https://libgen.li/ads.php?md5=7b969a8129a16b2f3679f4d4a20fff5d){:target="_blank"}

* [H. Pedrycz (2022). *Automata Theory and Formal Languages*.](https://libgen.li/ads.php?md5=aec2fe8b00ce16488082b14183d31727){:target="_blank"}

### Referencias avanzadas:

* [C. Papadimitriou (1994). *Computational Complexity*.](https://libgen.li/ads.php?md5=2e57188472acbbbb8b5860a1327fba94){:target="_blank"}

* [M. Sipser (2013). *Introduction to the Theory of Computation*.](https://libgen.li/ads.php?md5=e8e586576c1b46e2e37b37c852c27dfd){:target="_blank"}

---
