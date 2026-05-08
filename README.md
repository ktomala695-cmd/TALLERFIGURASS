# Taller de POO: Figuras Geométricas

## 1. Descripción del Ejercicio
Este proyecto es un taller práctico en Python donde se aplican conceptos fundamentales de la Programación Orientada a Objetos (POO) exigidos en clase: Encapsulamiento, Herencia, Sobrescritura de métodos y Polimorfismo. El objetivo es calcular el área y perímetro de diferentes figuras geométricas, garantizando mediante validaciones que sus dimensiones siempre sean mayores a cero.

## 2. Explicación de las Clases
* **FiguraGeometrica (Clase Base):** Define los atributos privados `_ancho` y `_alto`. Utiliza decoradores `@property` y `@setter` para el encapsulamiento y lanza un `ValueError` si se intentan asignar valores menores o iguales a cero.
* **Cuadrado (Clase Hija):** Hereda de `FiguraGeometrica`. Su constructor recibe un único parámetro (`lado`), el cual se asigna tanto al ancho como al alto de la clase padre. Sobrescribe los métodos de área, perímetro y de impresión (`__str__`).
* **Rectangulo (Clase Hija):** Hereda de `FiguraGeometrica`. Recibe dos parámetros distintos (`ancho` y `alto`) y sobrescribe los métodos de cálculo correspondientes a su forma geométrica.

## 3. Evidencia de Ejecución
A continuación se muestra la captura de pantalla de la ejecución del archivo `main.py`, donde se evidencian:
- El cálculo de áreas y perímetros.
- La suma total usando polimorfismo.
- La validación de errores (encapsulamiento).
- La fecha y hora del sistema.

![Evidencia de ejecución](captura.png)
Rectangulo: Clase hija para figuras con ancho y alto distintos.
<img width="1918" height="822" alt="EJECUTADO" src="https://github.com/user-attachments/assets/68bbfab8-7601-4103-8720-c5fdf4c42af4" />
