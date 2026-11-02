# Sistema de Gestión — Equipo N° 4

[![Proyecto](https://img.shields.io/badge/Estado-Finalizado-brightgreen)](#)
[![Materia](https://img.shields.io/badge/Materia-Pr%C3%A1ctica%20Profesionalizante%201-blue)](#)
[![Cuatrimestre](https://img.shields.io/badge/Cuatrimestre-2C%202026-green)](#)
 
Repositorio oficial del proyecto integrador de la materia **Práctica Profesionalizante 1 (2C 2026)** — Equipo N° 4.

---

## 👥 Integrantes — Equipo N° 4

| Nombre y Apellido | Rol Principal |
| :--- | :--- |
| **Franco Abdala** | Comunicador y diseñador grafico |
| **Noelia Trifoglio** | Analista de datos |
| **Lucas Cuello** | Documentador |
| **Adriel Salinas** | Responsable de calidad |

---

## 📌 Descripción del Proyecto

Este proyecto analiza la evolución del sector eléctrico renovable en Argentina entre 2011 y 2025: cómo creció la generación, dónde se instalaron las centrales nuevas, qué tecnologías predominaron y a través de qué programas se incorporaron.

---

## 🗃️ Fuente de los Datos
 
**CAMMESA** (Compañía Administradora del Mercado Mayorista Eléctrico Sociedad Anónima): datos mensuales de fuentes renovables de energía eléctrica por central energética y de demanda total (2011-2026). Se analizó el período 2011-2025.
 
Los datos originales están en `data/raw/`, los procesados en `data/processed/` y la descripción de las variables, en el diccionario de datos dentro de `docs/`.
 
---

🎯 Objetivo del Análisis
 
Identificar y explicar los cambios en el ritmo de crecimiento, la ubicación, la tecnología y el financiamiento de las energías renovables en Argentina, y presentarlos en un dashboard interactivo.
 
**Objetivo académico:** aplicar buenas prácticas de ciencias de datos, desarrollo colaborativo, metodologías ágiles y control de versiones mediante Git/GitHub.

---

## 🛠️ Tecnologías y Herramientas

### Análisis y Visualización
- **OpenRefine:** limpieza y transformación de los datos.
- **Power BI:** construcción del dashboard interactivo.

### Gestión y Colaboración
- **Control de Versiones y Almacenamiento de Archivos:** Drive & GitHub
- **Gestión de Tareas:** Trello

---

## 🔍 Trabajo Realizado
 
El proyecto se organizó en tres sprints, con seguimiento de tareas en Trello. El trabajo siguió estas etapas:
 
1. **Obtención de los datos** de CAMMESA y definición de las preguntas de análisis.
2. **Limpieza y transformación** de los datos con OpenRefine.
3. **Análisis de los datos** para responder las preguntas planteadas y formular los insights.
4. **Diseño del dashboard** en Power BI, con seis pestañas de análisis.
5. **Documentación y presentación:** diccionario de datos, informe técnico, manual de usuario y presentación final.

---

## 📊 Resultados Principales
 
- **Crecimiento:** expansión explosiva entre 2018 y 2021 (pico de 133 % interanual en 2019) y freno marcado desde 2022.
- **Geografía:** Patagonia y Comahue pasaron de concentrar el 23 % de las centrales nuevas (2018-2021) a solo el 3 % (2022-2025).
- **Tecnología:** se pasó de grandes parques eólicos a instalaciones solares de menor escala.
- **Concentración:** la eólica es la principal fuente, y Buenos Aires y Chubut generan casi la mitad de la energía renovable.
- **Financiamiento:** de las licitaciones estatales (RenovAr) se pasó a contratos entre privados (MATER), que desde 2023 impulsan cerca de dos tercios de las centrales nuevas.

---

## ✅ Conclusiones
 
La saturación de la red de alta tensión (SADI) reconfiguró las inversiones: las centrales nuevas dejaron la Patagonia por Buenos Aires y el Centro, pasaron de grandes parques eólicos a parques solares más chicos y dejaron de depender de licitaciones estatales para apoyarse en acuerdos entre privados. La falta de transporte no frenó a las renovables, pero las obligó a adaptarse.
 
---

## 📂 Estructura del Repositorio

```text
Equipo_N4_PP1_2C_2026/
├── analysis/            # Archivos relacionados con el analisis realizado por el equipo.
├── data/                # Archivos de datos utilizados en el proyecto.
│   ├── raw/             # Datos originales sin modificar.
│   └── processed/       # Datos que fueron preparados/transformados.
├── docs/                # Documentación del proyecto, fichas, definiciones y otros documentos relevantes.
├── reports              # Informes, presentaciones u otros productos finales del proyecto.
└── README.md            # Documento principal de presentación y documentación del proyecto.
