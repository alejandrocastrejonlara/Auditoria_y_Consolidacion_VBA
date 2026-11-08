# Automatización Financiera, Teoría de Colas y Simulación en VBA

## Descripción del Repositorio
Este repositorio contiene un portafolio de macros, UserForms y scripts desarrollados en Visual Basic for Applications (VBA) para Microsoft Excel. Los proyectos abarcan desde la automatización de tareas contables y auditorías financieras, hasta la simulación estocástica de sistemas complejos (Teoría de Colas) y evaluación de escenarios de riesgo mediante el Método de Monte Carlo.

## Tecnologías Utilizadas
*   **Lenguaje:** Visual Basic for Applications (VBA)
*   **Entorno:** Microsoft Excel (Manipulación del DOM de celdas, ChartObjects, Formatos Condicionales Dinámicos).
*   **Conceptos Matemáticos:** Método de Monte Carlo, Cadenas de Markov, Convolución de Probabilidades, Teoría de Colas, Esperanza Matemática.

---

## Proyectos Destacados

### 1. Simulador Estocástico de Juego de Azar (Monte Carlo)
**Archivo:** `VBA/MonteCarlo_Juego_Dados.xlsm`
Este proyecto es un motor de simulación de Monte Carlo que evalúa el rendimiento financiero, la probabilidad de ruina y la probabilidad de éxito en un juego de tablero interactivo basado en el lanzamiento de 7 dados cargados. 
*   **Motor de Simulación:** Ejecuta $N$ simulaciones completas por partida, gestionando estados complejos como capital dinámico, puntos acumulados, multiplicadores de costo/premio y penalizaciones (pérdida de turnos).
*   **Probabilidad Teórica vs. Empírica:** Calcula la función de masa de probabilidad exacta para la suma de 7 dados asimétricos mediante programación dinámica/convolución, y la contrasta con las frecuencias observadas (Ley de los Grandes Números).
*   **Dashboard Automatizado:** El script limpia, formatea y renderiza los resultados directamente en la hoja de cálculo. Genera dinámicamente gráficos de barras (`ChartObjects`) y aplica un **Mapa de Calor (Heatmap)** sobre las casillas del tablero real en Excel según la frecuencia de caída.

### 2. Simulación de Líneas de Espera (Teoría de Colas)
Script de automatización en Visual Basic for Applications (VBA) diseñado para consolidar, validar y auditar registros de ventas distribuidos en múltiples hojas de cálculo no estandarizadas.
