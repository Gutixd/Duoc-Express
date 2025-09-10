📦 Sistema de Gestión de Envíos – Duoc Express

Aplicación de consola desarrollada en Kotlin como parte de la evaluación parcial de la asignatura Desarrollo de Aplicaciones Móviles (DSY1105).
El proyecto implementa conceptos fundamentales de programación y buenas prácticas de desarrollo orientado a objetos.

🚀 Funcionalidades

Registro de envíos con validación de datos.

Jerarquía de clases con herencia y polimorfismo.

Manejo de colecciones (List, MutableList) y funciones de orden superior (filter, map, sumOf).

Simulación de procesamiento de envíos mediante corrutinas (suspend fun, delay).

Gestión de estados con clases selladas (sealed class).

Control de errores con try-catch para evitar fallos por entradas inválidas.

🛠️ Tecnologías

Lenguaje: Kotlin

IDE recomendado: IntelliJ IDEA

📂 Estructura del Proyecto

Envio → Clase base.

EnvioExpress, EnvioNormal → Clases hijas.

EstadoProcesamiento → Clase sellada para modelar estados.

Main.kt → Punto de entrada con lógica principal y simulación de procesamiento.

▶️ Ejecución

Clonar el repositorio.

Abrir en IntelliJ IDEA.

Ejecutar Main.kt desde la consola
