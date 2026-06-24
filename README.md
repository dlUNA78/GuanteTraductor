# 🧤 Intérprete de Lenguaje de Señas Mexicano (LSM) - Interfaz Hardware/AI

Un prototipo de sistema *end-to-end* diseñado para capturar movimientos físicos de la mano y traducirlos a texto en tiempo real mediante el uso de microcontroladores y algoritmos de Machine Learning. 

## 🎯 Objetivos y Logros del Proyecto

El objetivo principal fue construir un puente entre la accesibilidad y la tecnología. A través de este prototipo, se logró interpretar exitosamente diferentes letras y palabras completas del LSM, procesando la flexión de los dedos y la orientación espacial de la mano.

En este desarrollo me enfoqué específicamente en:
*   Creación de *datasets* personalizados para pruebas y entrenamiento del modelo.
*   Desarrollo de los *scripts* de clasificación y lógica en Python.
*   Conexión, calibración y *testing* de los sensores hacia el microcontrolador.

## 🛠️ Stack Tecnológico y Hardware

**Software & Procesamiento de Datos:**
*   **Lenguajes:** Python, C/C++
*   **Machine Learning:** Scikit-learn (para el entrenamiento y clasificación de gestos)
*   **Recolección:** Creación de Datasets propios

**Componentes Físicos:**
*   **Microcontroladores:** Placas Arduino y ESP32
*   **Sensores:** Sensores Flex (medición de articulaciones) y Acelerómetros (orientación espacial)
*   **Estructura del Wearable:** Guante de licra, cinta de nylon para ruteo de cables y pegamento flexible E6000


## 🚀 Estado Actual y Futuras Mejoras
*Proyecto en fase de refactorización de hardware.* Actualmente, la lógica de software y los modelos de clasificación son completamente funcionales. Se está investigando la integración de materiales conductores más flexibles (como hilo conductivo o Velostat) para reemplazar los sensores iniciales y aumentar la durabilidad física del *wearable* ante el movimiento constante.
