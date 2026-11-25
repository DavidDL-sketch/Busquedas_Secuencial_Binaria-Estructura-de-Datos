# Prácticas de Algoritmos de Búsqueda en Java

Implementación y análisis de los algoritmos de **Búsqueda Secuencial** y **Búsqueda Binaria** en lenguaje Java, como parte de las actividades prácticas de programación.

---

## 📋 Datos de Identificación

* **Alumno:** David Domínguez López
* **Asignatura:** Estructura de Datos
* **Institución:** Instituto Tecnológico Superior de Xalapa (ITSX)

---

## 📂 Contenido del Repositorio

1. **`PracticaBusquedaSecuencial.java`**: Implementación de búsqueda lineal sobre un arreglo de calificaciones no ordenadas.
2. **`PracticaBusquedaBinaria.java`**: Implementación de búsqueda binaria iterativa sobre un arreglo de folios previamente ordenados de forma ascendente.

---

## 🔍 Descripción de los Algoritmos

### 1. Búsqueda Secuencial (Lineal)
Recorre el arreglo elemento por elemento desde el índice `0` hasta `arr.length - 1`, comparando cada posición con la clave buscada.
* **Requisito:** Ninguno (funciona en arreglos ordenados y desordenados).
* **Complejidad temporal:** O(n) en el peor caso, O(1) en el mejor caso.

### 2. Búsqueda Binaria
Divide repetidamente a la mitad el intervalo de búsqueda comparando la clave con el elemento central (`mid`). Si no coinciden, descarta la mitad donde no puede encontrarse el valor.
* **Requisito:** El arreglo debe estar **previamente ordenado**.
* **Complejidad temporal:** \(O(\log n)\) en el peor caso, O(1) en el mejor caso.

---

## 🚀 Cómo Ejecutar los Programas

Asegúrate de tener instalado el **JDK (Java Development Kit)** en tu equipo.

1. Clona este repositorio o descarga los archivos `.java`.
2. Abre una terminal en la carpeta donde se encuentran los archivos.
3. Compila y ejecuta cada práctica con los siguientes comandos:

### Práctica 1: Búsqueda Secuencial
```bash
javac PracticaBusquedaSecuencial.java
java PracticaBusquedaSecuencial
```
**Salida esperada:**
```text
Posicion de 88: 3
Posicion de 100: -1
```

### Práctica 2: Búsqueda Binaria
```bash
javac PracticaBusquedaBinaria.java
java PracticaBusquedaBinaria
```
**Salida esperada:**
```text
Indice de 173: 5
Indice de 130: -1
```
