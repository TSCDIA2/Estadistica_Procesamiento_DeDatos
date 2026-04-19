# Gestión Universitaria - Dashboard de Estadísticas y Procesamiento de Datos

Este repositorio contiene la primera evidencia de aprendizaje para el módulo que integra las materias **Procesamiento de Datos** y **Estadística y Exploración de Datos 1**.

## 🚀 Vision del Proyecto: Universidad Privada

El proyecto surge de la necesidad de optimizar la gestión académica y financiera de los estudiantes en un entorno de educación privada. El "Pain Point" identificado se centra en la **impracticidad e ineficiencia** en el seguimiento de actividades críticas, lo que genera fricciones tanto administrativas como económicas para el estudiantado.

### 🚩 Problemática (Pain Point)
Los alumnos enfrentan dificultades para mantenerse al día con:
- Pago de cuotas y matrículas.
- Inscripción a materias y mesas de examen.
- Elección de turnos y comisiones.
- Entrega de actividades evaluables.

La ausencia de un sistema de notificaciones proactivo deriva en recargos por mora y pérdida de oportunidades académicas.

---

## 👥 Equipo de Trabajo
*   **Nombre del Grupo:** Undefined
*   **Integrantes:**
    1.  **Franco Arce** - GitHub: `Franco-Arce` - Email: `Francogonzaloarce@gmail.com`
    2.  **Yanina Roldán** - Email: `yanina88roldan@gmail.com`
    3.  **Shirley Frassa** - Email: `slfrassa@gmail.com`
    4.  **Gabriel Yoles Trucco** - Email: `gyoles96@gmail.com`
    5.  **Fabricio Cocconi** - Email: `fabriciococconi@gmail.com`
    6.  [Pendiente]

---

## 📋 Historias de Usuario (Backlog Inicial)

| Prioridad | Historia de Usuario | Descripción |
| :--- | :--- | :--- |
| **Alta** | Alerta de Vencimiento de Cuotas | Notificaciones 10 días y 1 día antes del vencimiento. |
| **Media** | Notificación Mesas Finales | Alerta automática 15 días antes del inicio de exámenes. |
| **Baja** | Recordatorio Actividades | Alerta 3 días antes del vencimiento de entregables. |

---

## 📊 Datos
La carpeta `/Datos` contiene el dataset principal en formato `.CSV` con la información necesaria para el análisis estadístico y procesamiento de datos.

### Características del Dataset:
- **Formato:** `.CSV` (disponible en `Datos/dataset_universidad.csv`)
- **Registros:** 500
- **Variables:**
    1. `id_alumno`: Identificador único.
    2. `nombre_completo`: Nombre y apellido ficticio.
    3. `carrera`: Carrera que cursa (Ingeniería, Licenciatura, etc.).
    4. `anio_ingreso`: Año de matriculación inicial.
    5. `cuotas_pendientes`: Cantidad de meses adeudados (0 a 12).
    6. `monto_deuda`: Deuda total calculada (cuotas * valor base).
    7. `promedio_general`: Promedio académico actual.
    8. `materias_aprobadas`: Cantidad de materias aprobadas a la fecha.
    9. `estado_alumno`: Situación académica (Regular, Libre, Suspendido).
    10. `notificacion_activa`: Si el alumno tiene habilitadas las alertas en la APP.

---

## 🛠️ Tecnologías Utilizadas
- **Python / R** (para procesamiento y estadística)
- **Git / GitHub** (control de versiones)
- **Markdown** (documentación)
