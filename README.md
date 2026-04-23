# Gestión Universitaria

## 🚀 Visión del Proyecto: Seguimiento Académico-Laboral

El proyecto surge de la necesidad de optimizar y medir el éxito de trayectorias universitarias cruzando información académica con datos de empleo del mundo real (formal). El objetivo principal es poder hacer ciencia de datos sobre la vinculación de estudios superiores y mercado de trabajo.

### 🚩 Problemática
Existe dificultad por parte de universidades y entes gubernamentales para entender y predecir:
- ¿Cuáles carreras tienen mejor o peor inserción en el sector privado?
- ¿Qué nivel salarial en blanco alcanzan recién egresados según rama de estudio?
- ¿Existe brecha salarial por género en los profesionales entre 2 y 4 años de egreso?
- ¿Qué tamaño de empresa absorbe a los distintos perfiles de graduados?

Esta desconexión genera escasez de estrategias políticas y decisiones de mercado informadas por datos empíricos.

---

## 👥 Equipo de Trabajo
*   **Nombre del Grupo:** Undefined
*   **Integrantes:**
    1.  **Franco Arce** - GitHub: `Franco-Arce` - Email: `Francogonzaloarce@gmail.com`
    2.  **Yanina Roldán** - GitHub: `YaninaRoldan` - Email: `yanina88roldan@gmail.com`
    3.  **Shirley Frassa** - GitHub: `sfrassa` - Email: `slfrassa@gmail.com`
    4.  **Gabriel Yoles Trucco** - GitHub: `gyoles` - Email: `gyoles96@gmail.com`
    5.  **Fabricio Cocconi** - GitHub: `Fabricio-Cocconi` - Email: `fabriciococconi@gmail.com`

---

## 📋 Historias de Usuario (Backlog Inicial)

| Prioridad | Historia de Usuario | Descripción |
| :--- | :--- | :--- |
| **Alta** | Modelo Predictivo Salarial | Desarrollar un modelo que prediga el sueldo esperado según disciplina académica. |
| **Media** | Perfilado de Retención del Talento | Entender mediante clústers los perfiles de graduados que ingresan a grandes empresas Vs PyMEs. |
| **Baja** | Dashboard Tasa de Empleo | Generar un tablero con la evolución de la ocupación salarial de egresados de 2016-2018. |

---

## 📊 Datos
La carpeta `/Datos` contiene el dataset principal en formato `.CSV` y su respectivo archivo Excel de metadatos (Diccionario) provistos por el CEP XXI.

### Características del Dataset:
- **Archivo:** `base_araucano.csv` (Microdatos)
- **Registros:** > 820.000 (cruce Araucano-SIPA)
- **Variables Críticas Analizadas:**
    1. `disciplina_id`: Rama específica de la carrera.
    2. `gestion_id`: Ámbito académico (Público vs Privado).
    3. `genero_id`: Sexo biológico del graduado.
    4. `salario`: Nivel de ingresos en pesos (cuantitativa continua).
    5. `tamaño_id` y `letra_id`: Magnitud y sector de la empresa contratante.

---

## 🛠️ Tecnologías Utilizadas
- **Python** (para procesamiento y estadística)
- **Git / GitHub** (control de versiones)
- **Markdown** (documentación)
