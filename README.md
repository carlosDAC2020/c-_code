# c-_code
ejercicios de algoritmos en c++

indice de ejercicios de practica


apliaccion de ciclos y condicionales 
problemario UTB pagina 69
----> 1 suma_fibonachi.cpp :calcule la suma de los terminos de la serie de FIBONACCI
cuyos valores se encuentran entrre 100 y 10,000 

----> 2 print_n_primos.cpp :imprimir n numeros primos

----> 3 n_pares.cpp :imprime los numeros pares entre 1 y n

----> 4 n_impares.cpp :imprime los numeros impares entre 1 y n

----> 5 prom_est.cpp : promedio de un numero desconocido de estiudiantes

----> 6 n_parejas.cpp : ingresar n parejas de numeros y decir si es mayor o menor y si son iguales

----> 7 prom_pesos.cpp : proomedio de pesos por distintas categorias

----> 8 prom_tiempos.cpp ; evalauacion de un atleta para la prueba se 5 km  

----> 9 angri_birds.cpp : aplicacion del mpvimien to parabolico uniforme usando bucles y condicionales


aplicacion de estructuras de datos listas tuplas matrives etc 
problemario UTB pagina 101
----> 10 cero_impar.cpp : en una lista de n elementos combertir los elementos impares en cero 

----> 11 f_listas.cpp : cramos algunas funciones que realicen operaciones bacicas entre vectores

---> 12 orden_listas.cpp: a partir de una lista en desorden la ordenamos de mayor a menor y veceberza


aplicacion de conocimientos generales
---> 50 funciones_random.cpp : en este archivo se encuentran funciones cono
                    matematicas basicas                            name                    librerias    probadas
            # evaluar si un numero es par 0 impar ---> linea 10  : par_impar()              >>  none       si
            # evaluar si un numero es primo o no  ---> linea 21 : n_primo()                 >>  none       si
            # hayar el factorial de un numero     ---> linea 36 : factorial()               >>  none       si
            # hayar el valor absoluto de un numero---> linea 46 : valor_obsoluto()          >>  none       si
        

                   listas y matrices
            # crear una lista con numeros aleatorios-> linea 58 : create_lista()            >>  stdlib.h   si
                                                                                                time.h
            # craer una matrix con numeros aleatorios> linea 75 : create_matriz()           >>  stdlib.h   si
                                                                                                time.h
            # hayar diagonal primcipal            ---> linea 208 : diagonal_1()             >>  none       si
            # hayar diagonal segundaria           ---> linea 229 : diagonal_2()             >>  none       si
            # suma de cada fila                   ---> linea 251 : sum_filas()              >>  none       si
            # suma de cada columna                ---> linea 273: sum_columnas()            >>  none       si
            # mayor elemento de cada fila         ---> linea 294: may_elemento_filas()      >>  none       si
            # mayor elemento de cada columna      ---> linea 317: may_elemento_coliumnas()  >>  none       si
            # menor elemento de cada fila         ---> linea 339: men_elemento_filas()      >>  none       si
            # menor elemento de cada columna      ---> linea 362: men_elemento_coliumnas()  >>  none       si
            # promedio de cada fila               ---> linea 385: promedio_filas()          >>  none       si
            # promedio de cada columna            ---> linea 409: promedio_columnas()       >>  none       si
            # suma de triangular superior         ---> linea 432: triangular_1()            >>  none       si
            # suma de triangular inferior         ---> linea 449: triangular_2()            >>  none       si

                    ordenamiento
            # funcionn del ordenamiento de una lista

 programacion orientada a objetos
-- definiciones de conceptos basicos
        # clases : una clase es simplemente un abtraccion que hacemos
          de nuestra experiencia sencible. El ser humano tiende a agrupar
          seres o cosas -onjetos- con caracteristicas similares en grupos
          -clases-

        # objeto : es un conjunto de atributos y metodos, un objeto se 
          deriva de una clase

        # abstraccion : proceso mental de selecion de caracteristicas esenciales
          de algo, ignorando los detalles superfluos o menores

        # encapsulacion : proceso en que se ocultan los detalles del soporte
          de las caracteristicas de una abstraccion

        # heremcia : la herencia es donde una clase nueva se crea a partir 
          de una clase existente, heredando todos sus atributos.

        # polimorfismo : se entiende por aquella cualidad que poseen los objetos
          para responder de distint0 modo ante el mismo mensaje

  ejemplos
--> 1 clases.cpp : creamos nuestras primeras clases aplicando los onceptos
                   enteriormente dichos

--> 2 rectangulo.cpp: construimos una clase llamada rectangulo que tenga
                   con atrinbutos de largo y ancho y los metodos de 
                   perimetro() y area()

--> 3 sobrecarga_cnstres.cpp : aplicacion de la funcion sobrecarga de 
                   constructores en los objetos usando un ejemplo con las fechas

--> 4 tiempo.cpp :  se construye una clase tiempo que contenga los siguientes
                    atributos enteros: horas, minutos y segundos hacemos 
                    que la clase contenga 2 constructores uno con 3 parametros enteros
                    que representan las hoaras, minutos y segundos y otro con un 
                    parametro de numero long que sdera la cantidad de segundos el cual 
                    se deber representar en horas minutos y segundos  

--> 5 destructor.cpp : implementacion de un destructor de objetos

--> 6 get_set.cpp : intruduccion y aplicacion de los metodos constructores y modificadores
                    getters y setters

--> 7 herencia.cpp : aplicacion de la hrencia en c++

--> 8 polimorfismo.cpp : aplicacion del polimorfismo en c++

--> 9 ejercicio.cpp : crear un programa en c++ con una jerarqui de clases
                      siendo animal la clase padre y humano y perro las subclases
                      aplicar polimorfismo en usando un metodo correr  
