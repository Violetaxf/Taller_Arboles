# Taller_Arboles
Taller 3: Árboles de búsqueda, 2024-30
Evaluación
La entrega se hará a través de la correspondiente asignación de BrightSpace. Se debe entregar un
único archivo comprimido, nombrado con el apellido correspondiente de cada integrante y
finalizando con la palabra “T3”, estos datos deben ir separados por “_” ejemplo:
“apellido1_apellido2_T3.zip”
Este archivo debe contener el documento de diseño y las justificaciones (.pdf) y el código fuente de
los programas (.h, .hxx, .cxx, .cpp).
- La inclusión de archivos en cualquier otro tipo de formato diferente a los especificados
(como archivos de proyecto de Dev-C++ o CodeBlocks) o el envío del archivo comprimido
en otro formato diferente a los especificados, resultará en una calificación de 0 (cero)
sobre 5 (cinco) para la entrega respectiva. Los archivos enviados DEBEN poderse compilar
y ejecutar SIN errores usando los comandos vistos en el taller 0.
- Para calificar el taller se deben cumplir todos los requerimientos solicitados, si no se
cumplen, se penaliza con -1.5.
No olvide aplicar correctamente el tema visto de composición para hacer un diseño e
implementación adecuado.
SISTEMA:
Un árbol de búsqueda binario es una estructura de datos en la cual cada nodo tiene, como
máximo, dos hijos: un hijo izquierdo y un hijo derecho. En este caso, se busca implementar este
tipo de árbol en un parqueadero con el propósito de agilizar la búsqueda y organización de los
vehículos.
Mantener el árbol balanceado es esencial para asegurar un óptimo rendimiento y asegurar una
complejidad logarítmica en las operaciones de búsqueda, inserción y eliminación. Un árbol se
considera balanceado cuando la diferencia de altura entre el subárbol izquierdo y el subárbol
derecho de cualquier nodo es, como máximo, 1. Esto garantiza que las operaciones de búsqueda
y otras operaciones mantengan un rendimiento eficiente y no se vuelvan lentas.
Para el sistema que se quiere implementar se deben guardar los siguientes datos de los
vehículos:
- Placa
- Marca
- Color
- Tipo de vehículo (Moto, Automóvil, Microbús)
- Es un vehículo para servicio público o no.
- Fecha y hora de entrada
Se debe contar con varias sedes de parqueaderos los cuales tienen:
- Identificador
- Nombre del parqueadero
- Cantidad máxima de vehículos
- Pago por minuto (para las motos es la mitad de este valor)
- Cada parqueadero debe tener una estructura adecuada para guardar los vehículos. (tener
en cuenta que cuando un vehículo sale del parqueadero, también se debe quitar de la
estructura)
Se le pide que desarrolle una primera versión de este sistema y debe realizar lo siguiente.
- (20%) Diseño de TADs siguiendo la plantilla vista en clase.
- (10%) Diagrama de TAD 's que muestre el diseño del sistema.
- (10%) Cargar datos iniciales usando un archivo de texto. Se deben cargar como mínimo 2
(parqueaderos), y por cada parqueadero mínimo 30 vehículos desde archivos de texto o
csv. Debe armar la estructura de parqueaderos con esos datos. (Es decir que su código no
debe pedir datos por consola para llenar los árboles).
- (15%) Realice un plan de pruebas para la función de “postorden”.
- (20%) Dado un id de parqueadero, haga una función que retorne la cantidad de dinero que
el parqueadero ganaría hasta ese momento solamente para vehículos particulares. Genere
una prueba para esta función.
- (25%) Dado un id de parqueadero y una placa, genere una función que retire ese vehículo
del parqueadero y retorne el valor que debe pagar. Use la función de “pre orden” para
realizar una prueba y validar que el árbol quedó correctamente balanceado después de la
eliminación. Seleccione un vehículo que esté en el nivel 3 del árbol.
- NOTA: Para las 3 pruebas debe usar el plan de pruebas como se ha realizado en los otros
talleres y proyectos.
Para la entrega debe incluir:
1) Archivos que usó para llenar los árboles.
2) Un archivo de texto donde indique los comandos que se deben usar para:
a) cargar datos iniciales.
b) Llamar la función de obtener el dinero hasta ese momento.
c) Llamar la función de retirar un vehículo y retornar el valor a pagar.
3) Un documento pdf con los pantallazos del funcionamiento del sistema.
4) Un documento pdf con los TAD y el Diseño.
5) Un documento pdf con el plan de pruebas.
