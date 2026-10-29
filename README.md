# Proyecto Snake (Fase Inicial)

Integrantes del equipo:

**- Juan Felipe Hoyos Bernate**

**- David Santiago Bernal Vargas**

Repositorio oficial para el desarrollo del videojuego clásico **Snake** en Java. Actualmente se encuentra en la **fase de análisis, diseño arquitectónico y configuración inicial**, siguiendo los lineamientos de arquitectura en capas y patrón DAO de la Universidad Libre.

## Stack Tecnológico Proyectado
* **Lenguaje:** Java (JDK 17)
* **Interfaz Gráfica:** Java Swing
* **Persistencia:** JDBC + Patrón DAO (Base de datos en la nube)
* **Metodología:** Desarrollo Guiado por Pruebas (TDD) con JUnit 5

## Arquitectura del Sistema
El diseño estructural está dividido en 4 paquetes exactos:
* `PQ GUI`: Capa de presentación (Vistas con Java Swing).
* `PQ Negocio`: Lógica central del juego (`SnakeController`).
* `PQ Datos`: Clases DTO con encapsulamiento en español (`obtener...` / `modificar...`).
* `PQ Persistencia`: Interfaces DAO, clase implementadora y conexión.

## Documentación
Los requerimientos detallados del sistema y el modelo de clases conceptual se encuentran documentados en la **Wiki** del repositorio.

## 🚀 Estado Actual
* Estructura de paquetes y diseño conceptual validados.
* Preparados para inicializar el entorno de desarrollo en IntelliJ IDEA e iniciar la codificación bajo TDD.
