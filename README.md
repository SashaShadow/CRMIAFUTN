# 🏥 CRM Instituto Alexander Fleming — Trabajo Práctico Integrador

> **Materia:** Organización Empresarial  
> **Carrera:** Tecnicatura Universitaria en Programación  
> **Institución:** Universidad Tecnológica Nacional (UTN)  

---

## 📌 Información del Proyecto

* **Título del Proyecto:** Desarrollo e Implementación de un Sistema CRM para la Gestión e Integración de Pacientes.
* **Organización / Caso de Estudio:** Instituto Alexander Fleming (IAF) — Clínica médica privada monovalente especializada en oncología (Colegiales, CABA).
* **Alumno:** Sasha Rodriguez Carlomagno.
* **Docente Titular:** Lopez Mario Raúl.
* **Docente Tutor:** Corts Romeo Franco Nicolás.
* **Año y cuatrimestre vigente:** Segundo cuatrimestre de 2026.

---

## 🚀 Descripción del Sistema

El proyecto consiste en el análisis, modelado y diseño de un **Sistema de Gestión de Relaciones con Clientes (CRM)** orientado a optimizar la atención y el flujo de trabajo del área de **Admisión de Pacientes y Agendamiento de Turnos** del Instituto Alexander Fleming.

A diferencia de las herramientas aisladas existentes (HISS, sistema de facturación e intranet), el CRM actúa como un **orquestador centralizado** que reúne en una sola interfaz la **ficha completa de atencion del Paciente**:
* **Datos Patronímicos e Identificación:** Consulta por DNI, Libreta de Enrolamiento o HCE.
* **Historial Integral:** Visualización unificada de turnos pasados, turnos del día y citas futuras.
* **Cobertura y Prestaciones:** Estado de obra social/prepaga y validación de órdenes médicas o coseguros.
* **Gestión de contactos:** Trazabilidad de contactos, notificaciones por correo electrónico, WhatsApp y aplicación mobile del sanatorio.
* **Seguridad y Control de Acceso:** Sistema de sesiones, roles y permisos específicos para cada área funcional.

## 🧰 Tecnologías y Herramientas Utilizadas

* **Metodología y Análisis:** Teoría General de Sistemas (TGS) y Notación BPMN 2.0.
* **Modelado de Datos:** TypeScript / Diccionario de Datos estructurado (`Patient`, `Turno`, `UserSession`).
* **Herramientas de Diagramado:** [BPMN.IO](https://demo.bpmn.io/).
* **Control de Versiones:** Git & GitHub.

# 🤖 Declaración de Transparencia y Uso Crítico de IA

En cumplimiento con las pautas del trabajo práctico integrador, se declara la utilización de asistentes de Inteligencia Artificial (ChatGPT y Gemini Notebook) como herramientas de apoyo técnico, conceptual y visual. A continuación se detallan los prompts utilizados, su justificación crítica y las correcciones humanas realizadas sobre los resultados obtenidos:

---

## 1. Detalle de Prompts Utilizados y Justificación de Uso

* **Consigna 1 — Modelado Organizacional (TGS):**
  * **Prompt / Enfoque:** Se estructuró un prompt especificando las entradas, procesos de transformación, salidas y entorno del Instituto Alexander Fleming descritos en el marco teórico, solicitando la diagramación analítica como sistema abierto.
  * **Justificación:** Permitió acelerar la estructuración formal de los componentes visuales del diagrama del sistema.

* **Consigna 2 — Viabilidad y Planificación (Gantt):**
  * **Prompt / Enfoque:** Se proporcionó la tabla de tareas, precedencias y estimaciones de plazos temporales a 6 meses para que el agente ChatGPT genere la representación en diagrama de Gantt.
  * **Justificación:** Facilitó la organización gráfica y la distribución temporal secuencial del proyecto.

* **Consigna 3 — Organigrama del area de Sistemas:**
  * **Prompt / Enfoque:** Se pide al agente Notebook/Gemini de Google la elaboración visual del organigrama que representa la estructura jerárquica del área de sistemas en la empresa.
  * **Justificación:** Permitió acelerar el desarrollo visual del organigrama.

* **Consigna 4 — Gestión por Procesos:**
  * **Prompt / Enfoque:** Se solicitó una síntesis/resumen de la teoria del diagramado BPMN y guía para comenzar el mismo.
  * **Justificación:** Sirvió como borrador inicial para mapear la secuencia de actividades, compuertas lógicas y roles del sanatorio en un modelo BPMN.
  * **Prompt / Enfoque:** Se solicitó la elaboración del archivo markdown para el README.md a partir del texto ingresado.
  * **Justificación:** Aceleró el armado estético de la documentación para el repositorio.

---

## 2. Correcciones Humanas y Análisis Crítico Efectuados

* **Verificación de Esquemas Visuales:** Para los esquemas visuales se verifica que el texto e información en los mismos sea la ingresada por el usuario y no alucinaciones de los modelos.
* **Corrección Iterativa del Flujo BPMN:** Se especifica de forma iterativa correcciones en el flujo de los procesos propios de la institución ante fallas o malos entendidos por parte de la IA al recomendar un flujo de modelado BPMN.
* **Formato y Estructuración:** Se corrigen detalles en la estructura del markdown.

