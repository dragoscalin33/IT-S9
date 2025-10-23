Creación de Funciones, Estructuras de Datos y Bucles

Objetivo del Proyecto

Este proyecto forma parte del Sprint 9 de Python y tiene como objetivo consolidar los fundamentos de la programación mediante la creación de funciones reutilizables, el uso de estructuras de datos (listas, tuplas, diccionarios) y el control de flujo a través de bucles y condicionales.

A partir de problemas de la vida cotidiana, se desarrollan diferentes programas sencillos que automatizan tareas útiles para un cliente ficticio.
El trabajo incluye desde cálculos básicos hasta procesamiento de datos y generación de contraseñas seguras.

⸻

Estructura del Repositorio

Archivo / Carpeta	Descripción
Tasca_S9_01.ipynb	Notebook de Jupyter con todos los enunciados, funciones y ejecuciones demostrativas.
historic_partits.txt	Archivo con datos reales de partidos de fútbol catalán, usado en el procesamiento de datos.
tu_me_quieres_blanca.txt	Texto utilizado para el análisis y conteo de palabras.
README.md	Este documento, con la descripción completa del proyecto.


⸻

Nivel 1 — Fundamentos Básicos

1. Calculadora del Índice de Masa Corporal (IMC)

Objetivo:
Crear una función que calcule el Índice de Masa Corporal (IMC) a partir de los datos ingresados por el usuario (peso y altura) y que clasifique el resultado en su categoría correspondiente según la OMS.

Características:
	•	Validación de datos de entrada (tipos y rangos razonables).
	•	Retorna el valor y la categoría del IMC.
	•	Muestra un mensaje de advertencia si los datos no son válidos.

⸻

2. Conversor de Temperaturas

Objetivo:
Desarrollar una función que convierta una temperatura dada entre al menos dos unidades distintas (°C, °F, K, etc.), devolviendo los resultados en un formato que pueda almacenarse (no solo con print()).

Extras:
	•	Validación de datos de entrada.
	•	Opción para guardar todas las conversiones en una estructura (lista, diccionario o DataFrame).

⸻

3. Contador de Palabras en un Texto

Objetivo:
Crear una función que, dado un texto, cuente cuántas veces aparece cada palabra.

Extras:
	•	Calcular la longitud media de las palabras del texto.
	•	Manejar casos con signos de puntuación o mayúsculas/minúsculas.

Ejemplo:

“Hola, ¿cómo va?” → Longitud media: (4 + 4 + 2) / 3 = 3.3

⸻

4. Diccionario Inverso (con Posibilidad de Duplicados)

Objetivo:
Desarrollar una función que reciba un diccionario y devuelva otro con las claves y valores intercambiados.

Extras:
	•	Si hay valores repetidos, mostrar una advertencia y listar las claves que comparten valor.
	•	Asegurar la integridad del nuevo diccionario.

⸻

Nivel 2 — Procesamiento de Datos

1. Contador y Ordenador de Palabras desde un Archivo

Objetivo:
Leer un archivo .txt y generar un diccionario ordenado alfabéticamente (A–Z) con la frecuencia de cada palabra.

Ejemplo de salida:

{
  "A": {"amor": 3, "ayer": 1},
  "B": {"blanca": 2, "busca": 1},
  ...
}

Archivo utilizado: tu_me_quieres_blanca.txt

⸻

2. Conversión de Tipos de Datos

Objetivo:
A partir de una lista mixta, generar dos nuevas listas:
	•	Una con todos los elementos que se pueden convertir a float.
	•	Otra con los que no se pueden convertir.

Ejemplo de entrada:

['1.3', 'one', '1e10', 'seven', '3-1/2', ('2',1,1.4,'not-a-number'), [1,2,'3','3.4']]


⸻

Nivel 3 — Automatización y Aleatoriedad

1. Generador de Contraseñas Seguras

Objetivo:
Diseñar una función que genere contraseñas aleatorias cumpliendo los siguientes parámetros:

Parámetro	Tipo	Descripción
longitud	int	Longitud de la contraseña.
mayusculas	bool	Incluir letras mayúsculas.
minusculas	bool	Incluir letras minúsculas.
numeros	bool	Incluir números.
signos	bool	Incluir símbolos especiales.

Ejemplo de ejecución:

crear_contrasenya(10, True, True, True, True)
# → 9Er,5Vn8P$

Extra:
Explorar cómo copiar automáticamente la contraseña al portapapeles (Ctrl+C).

⸻

2. Procesamiento de Datos de Partidos de Fútbol

Objetivo:
Analizar un archivo con resultados de partidos (historic_partits.txt) y generar:

Resultado Esperado	Descripción
Total de goles por equipo	Cuántos goles marcó cada equipo.
Equipo más goleador	Nombre del equipo con más goles.
Equipo más goleado	Equipo que recibió más goles.
Clasificación global	Puntuación total (3 pts por victoria, 1 por empate).

Ejemplo de salida esperada:

{
  "FC Barcelona": {"Goles a favor": 34, "Goles en contra": 12, "Puntos": 45},
  "Espanyol": {"Goles a favor": 21, "Goles en contra": 26, "Puntos": 31},
  ...
}


⸻

Entregables
	•	Un archivo .ipynb ejecutado con todo el código, funciones y resultados.
	•	Archivos de texto (historic_partits.txt y tu_me_quieres_blanca.txt) incluidos en el repositorio.
	•	Este README.md con la descripción completa del proyecto.

⸻

Duración y Objetivo General

Duración estimada: 10 días.
Objetivo final: Afianzar el dominio de:
	•	Sintaxis de Python
	•	Creación de funciones reutilizables
	•	Control de flujo (if, for, while, try-except)
	•	Manipulación de estructuras de datos
	•	Automatización de tareas cotidianas

⸻

Tecnologías y Herramientas
	•	Python 3.12+
	•	Jupyter Notebook
	•	NumPy
	•	Pandas
	•	Google Colab o VSCode
	•	GitHub

⸻

Conclusión

Este proyecto marca un punto clave en el aprendizaje de Python: pasar de entender la sintaxis a crear soluciones reales y reproducibles.
Cada ejercicio representa una pieza práctica de pensamiento lógico, diseño funcional y control de errores: la base de cualquier programador profesional.

⸻
