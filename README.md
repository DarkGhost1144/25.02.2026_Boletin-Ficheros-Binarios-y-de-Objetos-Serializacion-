# 25.02.2026_Boletin Ficheros Binarios y de Objetos Serializacion 

UD 12: Flujos de Entrada-Salida (Ficheros)
Ficheros Binarios
  1. Escribe como una cadena en el fichero binario cancionPirata.dat la siguiente estrofa:
  Con diez cañones por banda,
  viento en popa a toda vela,
  no corta el mar sino vuela,
  un velero bergantín.
  2. Recupera (lee) la estrofa del ejercicio anterior, pasa todo el texto a mayúsculas, e imprímelo por consola
  estándar.
  3. Pedir un entero n por consola, y, a continuación, pedir n números de tipo double, que iremos insertando en
  una tabla (un array) para, finalmente, guardar el contenido de la tabla en un archivo binario.
  4. Lee el fichero anterior, recupera los n doubles que contiene y almacénalos en un array. Finalmente, imprime el
  contenido del array.
Ficheros de Objetos (Serialización)
  5. Implementa una clase Socio que tenga 2 atributos: dni y nombre (ambos String). En una clase Principal, crea
  varios socios, mételos en una lista. A continuación, recorre la lista y guarda los socios en un archivo binario
  (Socios.dat). Por último, abre el archivo binario, recupera (lee) los socios del fichero e imprímelos por pantalla.
  6. Diseña una aplicación Java que trabaje con objetos de la clase Producto. De cada producto se guardará un id,
  nombre, precio y proveedor. La aplicación permitirá insertar productos, eliminar, consultar y listar productos.
  Para almacenar los productos utiliza un ArrayList y sobre esta estructura realiza las inserciones, eliminaciones,
  búsquedas y listados.
  Al finalizar la aplicación, guarda los objetos en un fichero binario y al empezar carga los objetos desde el
  fichero al ArrayList de forma que no se pierdan los objetos creados en ejecuciones anteriores.
  Clases:
  - Producto.
  - GestionProductos. Contiene el ArrayList y los métodos para añadir, eliminar (por id), consultar
  (buscar por id) y devolver el ArrayList. Esta clase también debe incluir los métodos para escribir/leer
  el arrayList en/del archivo.
  - Aplicación. Es la clase que contiene el main. Debe mostrar el menú con las opciones y el bucle de
  tratamiento del menú:
    Pulse 1 para cargar los datos de productos guardados en el archivo.
    Pulse 2 para añadir producto.
    Pulse 3 para eliminar producto.
    Pulse 4 para consultar los datos de un producto.
    Pulse 5 para imprimir el listado de productos.
    Pulse 6 para guardar los productos en un archivo.
    Pulse 0 para salir.
  Consejos para este ejercicio:
  - Primero resuelve sin archivos.
  - Cuando compruebes que funciona, añade la opción de leer datos al empezar y guardar datos al
  finalizar.
