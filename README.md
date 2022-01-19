<div align="center">
    <img src="https://programacioncetis104.milaulas.com/pluginfile.php/25/course/overviewfiles/89120b62-a53c-491d-a359-839b2f39971b.png" width="300px"> </img> 
    
<!-- Encabezado -->
## IS-310 | Algoritmos & Estructuras de Datos
### II PAC 2019 & III PAC 2019  
### Seccción 1500
### Catedratico **Ing. José Manuel Inestroza**

### Estudiante 
| Nombre | Numero De Cuenta | Correo Institucional |
|:-------------:| :-----:|:-----:|
| Edgar Josué Benedetto Godoy | `20171033802` | [UNAH](mailto:edgar.benedetto@unah.hn) |

</div>
_______
_______

## Estructuras de datos 
1. Listas enlazadas 
   1. Tipo Pila LIFO
   2. Tipo Cola FIFO
   3. Tipo Doblemente enlazada
   4. Tipo Circular
   5. Descendente
   6. Tipo JSON
2. Árboles
   1. Binary Search Tree o Árbol Binario de Búsqueda
   2. Heap Tree o Árbol Tipo Monticulo
3. Grafos
   1. Dirigidos
   2. No dirigidos
   3. De Listas Enlazadas
   4. Aristas con Pesos

## Algoritmos 
1. Algoritmos de ordenamiento
2. Algoritmos de Cifrado
3. Algoritmos de Busqueda

______

## Definiciones
### Encriptación
#### Etimologia:
* **encryption**: 
  * Es el proeso de codigicar un mensaje o informacion de tal manera que solo las partes autorizadas puedan acceder a el
* **Encoding**: 
  * El proceso de codificiacion convierte



* Cifrado Cesar
    * Es un cirfrado po desplazamiento se encarga de mover cada letra una cantidad de caracteres en el alfabeto puede ser n desplazamientos a la derecha o izquierda en honor a julio cesar quien uso desplaza,miento de 3 espacios e.g ADA = DGD

* Numero binarios
    * Es el sistema de escritura y calculo usando numeros que usan solo 2 digitos para su numeracion (0 y 1) Tiene 2 como base (unicamente cuenta con 2 digitos e.g base 10 con diez digitos, octal con 8 digitos Hexadecimal con 16 etc.)

* Operaciones Binarias
    * Las operaciones binarios convencionales son:
        1. AND (representado por el simbolo & ampersand)
        2. OR (representado por el simbolo)
        3. NOT
        4. XOR
        5. NAND
        6. NOR
_____

#### Principio basico:
1. Cifrar una letra con una letra.

```
01000100 --> 68
11111011
10111011 --> Utilizando XOR (XOR solo puede existir cuando uno es verdadero y otro es falso)
11111011
10111011
```

### Grafos

#### Todo árbol es un grafo pero no todo grafo es un árbol

* El grafo se compone de:
    1. Nodos --> Vertices, vertex
    2. Arcos --> Aristas, edge

#### Ejemplo
* Correspondencia donde el primero es por orden alfabetico
    * El vertice A tiene aristas con: B y C
    * El vertice B tiene aristas con: C y D
    * El vertice C no tiene aristas
    * El vertice D no tiene aristas
    * C Es una ruta final 
    * D Es una ruta final 
    
#### Observaciones
1. Al tener dirección este grafo tiene restricciones
2. Cada vertice será indice y cada elemento será un elemento en un arreglo de vertices como el valor de dicho indice

* Grafo Dirigido:
    * Diccionario equivale a Json en un grafo Dirigido
    * Una caracteristica de los grafos dirigidos, es posible producir ciclos(loops) pero también existen salidas naturales del grafo