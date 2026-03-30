```markdown
# Preparación para el Examen de Residencia de Medicina Interna

## Descripción General del Proyecto

Este proyecto está diseñado para ser una herramienta integral de estudio y preparación para el examen de Residencia de Medicina Interna. Su objetivo principal es generar un extenso banco de preguntas y conceptos médicos, modificados y verificados, para optimizar el proceso de aprendizaje y memorización. A través de la interacción con un asistente de IA especializado, se transformarán preguntas existentes y se crearán nuevas, asegurando la relevancia clínica y la adherencia a la literatura médica actualizada.

El banco de preguntas se estructurará de manera que permita la importación y gestión en una base de datos (MS Access), facilitando la creación de simulacros de examen dinámicos donde las preguntas y respuestas incorrectas se seleccionan aleatoriamente, evitando la memorización por patrón.

Paralelamente, se construirá un diccionario de conceptos médicos clave con definiciones concisas y completas, también para su integración en la base de datos y su uso como herramienta de repaso.

## Características Principales

*   **Modificación Dinámica de Preguntas:** Transformación de preguntas existentes para alterar su formulación o contexto, manteniendo la validez clínica.
*   **Generación de Respuestas Distractoras:** Creación de múltiples opciones de respuesta incorrectas plausibles para cada pregunta, aumentando la dificultad y la profundidad del estudio.
*   **Verificación y Explicación Detallada:** Cada pregunta y concepto incluye una justificación clínica completa y referencias bibliográficas actualizadas.
*   **Base de Datos Estructurada:** Formato de salida optimizado para la importación en MS Access, permitiendo una gestión eficiente y la creación de simulacros personalizados.
*   **Diccionario de Conceptos:** Definiciones concisas y completas de terminología médica esencial para residentes de Medicina Interna.
*   **Citas Basadas en Evidencia:** Todas las respuestas y explicaciones están respaldadas por la literatura científica y consensos actualizados.

## Estructura del Proyecto

El proyecto se compone principalmente de archivos de texto que serán generados y actualizados continuamente con las preguntas y conceptos.

*   `preguntas.csv`: Archivo principal que contendrá las preguntas modificadas, la respuesta correcta, las respuestas erróneas y la explicación.
*   `conceptos.csv`: Archivo que almacenará los conceptos médicos y sus definiciones.
*   `README.md`: Este archivo, con la descripción del proyecto y el seguimiento del progreso.
*   Otros archivos generados durante el proceso de importación o configuración de la base de datos.

## Guía de Uso (Workflow con IA)

1.  **Suministro de Preguntas/Conceptos:** El usuario proporciona preguntas originales (en texto o imagen) o solicita la definición de un concepto.
2.  **Procesamiento por IA:** El asistente de IA modifica la pregunta (si aplica), genera respuestas distractivas, verifica la información, añade una explicación detallada y referencias. Para los conceptos, proporciona una definición exhaustiva y referenciada.
3.  **Generación de Archivos CSV:** La IA entrega la información en un formato estructurado (e.g., CSV) listo para ser importado.
4.  **Importación a MS Access:** El usuario importa los archivos CSV a la base de datos de MS Access para su posterior gestión y uso en simulacros.

## Progreso del Proyecto

### **Estado Actual:**

*   **Fase 1: Configuración Inicial del Sistema y Asistente de IA.** (Completada)
*   **Fase 2: Definición de Formato de Salida para MS Access.** (En progreso - Pendiente de especificaciones de la DB)
*   **Fase 3: Construcción del Banco de Preguntas.** (Próxima a iniciar)
*   **Fase 4: Desarrollo del Diccionario de Conceptos.** (Próxima a iniciar)

### **Métricas (Estimadas):**

| Elemento             | Meta  | Actual | % Completado | Última Actualización |
| :------------------- | :---- | :----- | :----------- | :------------------- |
| **Preguntas Totales** | 1000+ | 0      | 0%           | N/A                  |
| **Conceptos Totales** | 500+  | 0      | 0%           | N/A                  |
| **Archivos CSV**     | 2     | 0      | 0%           | N/A                  |

---
**Este README se actualizará regularmente para reflejar el estado actual y el progreso del proyecto.**
