## Base de datos
Estructura cuya finalidad es contener y organizar porciones de informacion para luego facilitar su acceso en futuras ocasiones.

### Relacionales .
* Relaciones
* Transfaccionales
* Jerarquicas
* Orientadas a objetos
* Documentos

Estas estructuras solian estar vidididas en tablas y las mismas constan de los siguientes elementos:
__Campos(columna):__ Conjuntos de datos que corresponden a un _mismo tipo_. 
__Registros(fila):__ Conjunto de datos que guardan _relacion entre si_.
__Datos(Celda):__ Minima porcion de informacion.

* Tabla de colores
    | id | color |
    |-|-|
    | 1 | rojo |
    | 2 | azul |
    | 3 | verde |
    | 4 | purpura |
    | 5 | marron |
    | 6 | amarillo |
    | 7 | negro |

* Tabla de especies
    | id | especimen |
    |-|-|
    | 1 | humano |
    | 2 | primate |
    | 3 | canino |
    | 4 | felino |
    | 5 | paquidermo |
    | 6 | equino |
    | 7 | roedor |
    | 8 | dromedario |

* Tabla de personajes
    | id | personaje | especimen_id | color_id |
    |-|-|-|-|
    | 1 | symba | 4 | 6 |
    | 2 | kimba | 4 | 6 | 
    | 3 | lassie | 3 | 7 |
    | 4 | garfield | 4 | 6 | 
    | 5 | clifford | 1 | 3 | 

### NO relacionales (NOSQL).

