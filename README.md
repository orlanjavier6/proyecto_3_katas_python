# Proyecto 3: Lógica y Programación Funcional – Katas Python

Este proyecto forma parte del módulo de **Programación con Python** del Máster en Data & Analytics. 
Consiste en la resolución y documentación de un conjunto de **41 ejercicios prácticos (Katas)** enfocados en el desarrollo del pensamiento algorítmico, el paradigma de la programación funcional y la gestión robusta de datos e imprevistos en tiempo de ejecución.

La colección abarca desde la manipulación básica de estructuras de datos y lógica condicional, hasta conceptos avanzados como la recursividad, el uso de funciones de orden superior (`map`, `filter`, `reduce`), expresiones lambda y la Programación Orientada a Objetos (POO).

---

## Estructura del Proyecto
El repositorio está organizado para facilitar la inspección del código y la ejecución del entorno:

proyecto_3_katas_python/
├── Enunciado Data Project_Python.Lógica.pdf  # Documento original con las directrices y enunciados
├── Proyecto Lógica Katas Python.ipynb       # Jupyter Notebook principal con las 41 katas resueltas y ejecutadas
├── Proyecto_Lógica_Katas_Python.py          # Script de Python puro ejecutable en consola
└── README.md                                # Descripción general del proyecto y documentación

---

## Herramientas y Tecnologías Utilizadas
- **Python 3.x** → Lenguaje de programación principal del proyecto.
- **Jupyter Notebook** → Entorno interactivo utilizado para el desarrollo, pruebas y documentación en vivo de las celdas de código.
- **Módulos Nativos de Python:**
    - `functools` (específicamente la función `reduce`) para la agregación y acumulación de datos.
    - `math` para operaciones de precisión geométrica (cálculo de áreas).
- **Paradigma Funcional y POO:**
    - Estructuras Lambda (Funciones anónimas).
    - Métodos de orden superior: `map()`, `filter()`, `reduce()`.
    - Clases, constructores (`__init__`), encapsulamiento de estados y modelado de métodos de negocio.

---

## Proceso Metodológico de Desarrollo y Apoyo
1. **Lógica de Control de Flujo:** Implementación de estructuras condicionales anidadas (`if-elif-else`) para resolver problemas de negocio y toma de decisiones en tiempo real (ej. pasarelas de pago, cálculo de tiempos o tarifas horarias).
2. **Manipulación de Colecciones:** Uso extensivo de listas, diccionarios, tuplas y conjuntos (`sets`) aplicando técnicas de normalización de cadenas de texto (`.strip()`, `.lower()`, `.replace()`) para garantizar búsquedas e indexaciones robustas.
3. **Manejo Seguro de Excepciones:** Diseño de bloques `try-except-else` y creación de excepciones personalizadas (`class ErrorListaVacia`, `ErrorEdadFueraDeRango`, `ErrorNombreNoEncontrado`) para evitar fallos críticos ante entradas de usuario inválidas o errores lógicos como la división por cero.
4. **Modelado del Mundo Real (POO):** Diseño de clases complejas con estados mutables controlados por métodos específicos (ej. simulación de crecimiento de estructuras arbóreas en `Arbol` o consistencia transaccional y flujos de caja en `UsuarioBanco`).

***

**Nota sobre el proyecto:** Dado que este es un proceso de aprendizaje orientado a consolidar la lógica de programación y la sintaxis avanzada de Python, se utilizó apoyo de una IA para depurar flujos algorítmicos complejos, refinar el control de excepciones personalizadas y estructurar los casos de uso de forma óptima. Esto garantizó la entrega de código limpio, idiomático (*Pythonic*) y eficiente.

***

## Resultados y Conclusiones

- **Total de Katas resueltas:** **41 problemas algorítmicos** completados con éxito.
- **Análisis de Texto y Criptografía:** Creación de algoritmos para conteo de frecuencias de caracteres mediante diccionarios, verificación de anagramas empleando ordenamiento alfabético (`sorted`) y enmascaramiento dinámico de datos sensibles mediante técnicas de *slicing* (`[-4:]`).
- **Procesamiento de Datos Eficiente:** Transformación paralela de colecciones de datos limpiando elementos repetidos con estructuras algebraicas de conjuntos (`set`) en una sola línea de código.
- **Casos de Uso de Negocio Integrados:**
    - **Simulación Bancaria:** Un sistema de transferencias entre cuentas que asegura la integridad transaccional (bloquea la operación si el emisor no posee fondos antes de abonar al receptor).
    - **Orquestador de Textos:** Una función superior (`procesar_texto`) que recibe argumentos variables (`*args`) y delega dinámicamente tareas de conteo, reemplazo o eliminación de palabras.
    - **Computador Geométrico:** Uso de tuplas desempaquetadas para inyectar variables de dimensiones dinámicas según la figura seleccionada.

---

## Habilidades Demostradas

- **Programación Funcional Avanzada:** Reemplazo eficiente de bucles tradicionales (`for`/`while`) por operaciones optimizadas en memoria con `map()` y `filter()`.
- **Elegancia Código Sintáctico:** Reducción de lógica compleja de múltiples líneas a funciones anónimas `lambda` limpias y listas de comprensión eficientes.
- **Arquitectura Defensiva:** Validación proactiva de datos de entrada (rangos de edad de 0 a 120, horas de 0 a 23, división por cero) para asegurar que el software responda de forma controlada ante cualquier escenario anómalo.

---

## Acceso al Código
**Consulta el cuaderno completo con todas las celdas ejecutadas:**
[Abrir Proyecto Lógica Katas Python.ipynb](./Proyecto%20Lógica%20Katas%20Python.ipynb)

*(Para una visualización interactiva y óptima, se recomienda abrir el archivo directamente en Jupyter Notebook, JupyterLab o VS Code).*

---

## Próximos Pasos
- Migrar las funciones de procesamiento de colecciones hacia librerías de análisis de datos a gran escala como **Pandas**.
- Diseñar pruebas unitarias automatizadas (`unittest` o `pytest`) para verificar la resiliencia de las excepciones ante cientos de entradas de usuario aleatorias.

---

## Contribuciones
Las contribuciones y sugerencias son bienvenidas. 
Si encuentras una solución alternativa más eficiente para alguna Kata (*refactoring*), siéntete libre de abrir un *issue* o enviar un *pull request*.

---

## Autor
**[Orlan Javier Parra Parra]**
