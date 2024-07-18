# MyAPPXML

Conceptos Klotin
Podría ser un término específico de un marco o lenguaje de programación, pero si se relaciona con Kotlin (un lenguaje moderno de programación)

Variables Klotin
En Kotlin, las variables pueden ser:

Mutable: Se declaran con var, lo que permite cambiar su valor.

kotlin
Copiar código
var edad = 25
edad = 26
Inmutable: Se declaran con val, lo que significa que su valor no puede cambiar.

kotlin
Copiar código
val nombre = "Juan"

Constantes
Las constantes en Kotlin se definen utilizando val, y su valor es fijo una vez asignado.

Opciones
En el contexto de Kotlin, las "opciones" pueden referirse a los tipos opcionales (nullable), que permiten que una variable pueda tener un valor nulo. Se utilizan con el símbolo ?.

kotlin
Copiar código
var apellido: String? = null

Manejo de Nulos
Kotlin tiene un manejo de nulos muy seguro. Puedes usar:

Tipos no nulos: Por defecto, las variables no pueden ser nulas.
Tipos nulos: Para permitir nulos, se usa ?.
Operador de Elvis (?:): Permite proporcionar un valor por defecto si la variable es nula.
kotlin
Copiar código
val longitud = apellido?.length ?: 0
