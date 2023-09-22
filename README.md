# Laboratorio1_ED2
Laboratorio de Estructura de Datos 2 donde se implementan los conceptos de árboles AVL, factores de balanceo, miveles de un árbol, etc.

Debe construir un árbol que se auto balancee cada vez que se realice una acción,
conforme lo requiera dicha acción. Para construir el árbol debe utilizar la siguiente
métrica:




metric = price / surface_total




En caso de haber conflicto (valores de métrica iguales), se debe utilizar una
segunda métrica (la cual debe ser explicada en la sustentación) creada a partir
de los atributos del dataset provisto.




La información con la que debe construir el árbol se encuentra en el dataset
co_properties_final.csv que contiene la información de anuncios sobre venta y
arriendo de inmuebles en Colombia. Este dataset cuenta con 150 registros y
contiene los siguientes atributos:




• title: Titulo del anuncio del inmueble.
• department: Departamento donde está localizado el inmueble.
• city: Ciudad donde está localizado el inmueble.
• property_type: Tipo del inmueble (casa, apartamento, etc.).
• latitude: Latitud geográfica de la localización del inmueble.
• longitude: Longitud geográfica de la localización del inmueble.
• surface_total: Superficie total del inmueble.
• surface_covered: Superficie cubierta del inmueble.
• bedrooms: Número de cuartos del inmueble.
• bathrooms: Número de baños del inmueble.
• operation_type: Operación a realizar con el inmueble (compra, arriendo, etc.).
• price: Precio del inmueble según la operación.




En el árbol generado se debe poder realizar las siguientes operaciones:




1. Insertar un nodo.
2. Eliminar un nodo utilizando la métrica dada.
3. Buscar un nodo utilizando la métrica dada.
4. Buscar todos los nodos que cumplan con una serie de criterios (máximo 3).
Ejemplo:
(city = ‘Barranquilla’) & (bedrooms > 2) & (price <= 15000000)




5. Mostrar el recorrido por niveles del árbol (de manera recursiva).
Con los nodos obtenidos de las operaciones 3 y 4, se debe poder seleccionar uno
y realizar lo siguiente:




a. Obtener el nivel del nodo.
b. Obtener el factor de balanceo del nodo.
c. Encontrar el padre del nodo.
d. Encontrar el abuelo del nodo.
e. Encontrar el tío del nodo.




Adicionalmente, se debe mostrar gráficamente el árbol generado luego de cada
operación de inserción o eliminación (posterior a la generación inicial del árbol) y
cada nodo debe tener la información del dataset que le corresponda. Para esto
se puede apoyar en la librería graphviz en Python.




Bonificación: Geolocalizar en un mapa de Colombia los lugares obtenidos luego
de las operaciones 3, 4, c, d y e.



INTEGRANTES DEL GRUPO
1. LORENZO GUTIÉRREZ VESGA
2. HENRY SÁENZ VALVERDE
3. JUAN SEBASTIÁN QUINTANA 

