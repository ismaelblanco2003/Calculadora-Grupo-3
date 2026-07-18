# 🧮 Proyecto: Calculadora Colaborativa

¡Bienvenido al repositorio de la **Calculadora Colaborativa**! Este proyecto fue desarrollado como parte de una práctica de desarrollo de software utilizando metodologías ágiles y control de versiones con **Git & GitHub**. 

El objetivo principal de esta práctica es experimentar el flujo de trabajo en equipo, la resolución de conflictos de fusión (*merge conflicts*), la revisión de código a través de *Pull Requests* y el cumplimiento de estándares de desarrollo en un entorno simulado de producción.

---

## 🚀 Características del Proyecto
La calculadora cuenta con un conjunto de operaciones organizadas por módulos, implementando tanto operaciones aritméticas básicas como funciones avanzadas:
*   **Operaciones Básicas:** Suma, Resta, Multiplicación y División.
*   **Operaciones Avanzadas:** Potenciación, Raíz Cuadrada, Factorial y Módulo.
*   **Interfaz de Usuario:** Control por consola/terminal interactivo y limpio.
*   **Manejo de Errores:** Control robusto de excepciones (como la división por cero).

---

## 🛠️ Tecnologías Utilizadas
*   **Lenguaje:** Python 3.x
*   **Control de Versiones:** Git
*   **Plataforma de Alojamiento:** GitHub
*   **Entorno de Pruebas:** PyTest (para la validación de cada funcionalidad)

---

## 👥 Flujo de Trabajo Colaborativo (GitFlow Utilizado)
Para garantizar la integridad del código y simular un entorno profesional, el equipo siguió las siguientes directrices de ramificación:

1.  **`main`**: Contiene la versión de producción 100% estable.
2.  **`develop`**: Rama integradora donde se unen todas las características antes de pasar a producción.
3.  **Ramas de Características (`feature/nombre-operacion`)**: Cada desarrollador trabajó de forma aislada en una función específica. Por ejemplo:
    *   `feature/suma-resta`
    *   `feature/multiplicacion-division`
    *   `feature/avanzadas`

### 🔄 Reglas de Contribución (Branch Protection)
*   Está prohibido hacer `push` directo a la rama `main` y `develop`.
*   Todo cambio debe ser solicitado a través de un **Pull Request (PR)** hacia `develop`.
*   Cada PR requiere la revisión obligatoria y aprobación de al menos **un compañero de equipo (Code Review)** antes de ser fusionado.
*   Todas las pruebas automatizadas de la suite de testing deben ejecutarse de forma exitosa antes del merge.

---

## 💻 Instalación y Ejecución

Sigue estos pasos para clonar el proyecto y ejecutarlo de manera local:

### 1. Clonar el repositorio
```bash
git clone [https://github.com/tu-usuario/calculadora-colaborativa.git](https://github.com/tu-usuario/calculadora-colaborativa.git)
cd calculadora-colaborativa