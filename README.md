<p align="center">
  <img src="media/logo-volatixlab.png" width="180" alt="VolatixLab Logo">
</p>

# 🧠 VolatixLab

**VolatixLab** es un laboratorio de **análisis forense digital en español**, creado por [Adrián Gómez-Valadés Castaño](https://adriangvc.com).  
Su objetivo es ofrecer **escenarios realistas y educativos** para practicar análisis de memoria, disco y evidencias digitales con herramientas como **Volatility**, **Autopsy**, **FTK Imager**, y otras.

---

## ⚙️ ¿Qué es VolatixLab?

VolatixLab recopila **escenarios forenses prácticos** diseñados para el aprendizaje de técnicas de investigación digital y respuesta ante incidentes.  
Cada escenario incluye:

- 💾 **Evidencias reales** (RAM, disco, logs, etc.)  
- 🧠 **Descripción y contexto del incidente**  
- 🎯 **Objetivos y preguntas forenses**  
- 🕵️‍♂️ **Solución o writeup (opcional)**  
- 🔍 **Herramientas recomendadas**

Estos escenarios están creados para mejorar tus habilidades en **análisis forense**, **Blue Team**, y **ciberinvestigación**, todo en español.

---

## 📂 Estructura del repositorio

VolatixLab/
├── escenarios/ → Escenarios forenses listos para analizar
│ ├── plantilla-escenario/ → Plantilla base para nuevos escenarios
│ ├── escenario-01/ → Ejemplo real (Robo de credenciales)
│ └── ...
│
├── docs/ → Guías y documentación
│ ├── guia-creacion-escenarios.md
│ ├── herramientas-recomendadas.md
│ └── guia-analisis.md
│
├── scripts/ → Scripts útiles (hash, metadata, etc.)
│
└── media/ → Logo, capturas y material visual


---

## 🧩 Escenarios disponibles

| # | Nombre del escenario | Tipo de evidencia | Dificultad | Descripción breve |
|:-:|----------------------|------------------|-------------|-------------------|
| 01 | Robo de credenciales | Memoria RAM + Disco | 🟡 Media | Análisis de un posible robo de credenciales en un sistema Windows |
| — | Próximamente... | — | — | — |

> Cada escenario incluye su propia carpeta con documentación, evidencias y solución.

---

## 🧰 Herramientas recomendadas

- 🧠 [Volatility 3](https://github.com/volatilityfoundation/volatility3)
- 🔍 [Autopsy](https://www.autopsy.com/)
- 🧾 FTK Imager  
- 💽 HxD, Strings, RegRipper  
- 🌐 Wireshark, NirSoft Tools  

Consulta la guía completa en [`docs/herramientas-recomendadas.md`](docs/herramientas-recomendadas.md).

---

## 🧠 Cómo usar los escenarios

1. Descarga el escenario desde la carpeta `/escenarios/`.
2. Lee el archivo `README.md` del escenario para entender el contexto.
3. Abre las evidencias (RAM, disco, logs, etc.) con las herramientas recomendadas.
4. Intenta resolver las preguntas planteadas.
5. Consulta la solución (`solucion/writeup.md`) si quieres comparar tu análisis.

---

## 🧩 Cómo crear tu propio escenario

Si quieres contribuir o crear tus propios escenarios:

- Usa la plantilla de [`escenarios/plantilla-escenario/`](escenarios/plantilla-escenario/).  
- Sigue la guía en [`docs/guia-creacion-escenarios.md`](docs/guia-creacion-escenarios.md).  
- Incluye siempre:
  - Descripción y contexto.
  - Evidencias (RAM, disco, logs, etc.).
  - Objetivos o preguntas del análisis.
  - Archivo `metadata.json` con información técnica.
  - Carpeta `solucion/` con un `writeup.md` si quieres incluir la resolución.

---

## 🧾 Licencia

Este proyecto está bajo licencia  
**[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es)**  

📘 Puedes compartirlo y adaptarlo con atribución, **sin fines comerciales** y **bajo la misma licencia**.  
Cualquier redistribución debe incluir crédito a **Adrián Gómez-Valadés Castaño** y un enlace a [adriangvc.com](https://adriangvc.com).

---

## 👨‍💻 Autor

**Adrián Gómez-Valadés Castaño**  
📍 Don Benito / Badajoz  
🌐 [adriangvc.com](https://adriangvc.com)  
🧠 Ciberseguridad · Análisis Forense · Blue Team  

---

## 🖼️ Identidad Visual

VolatixLab mantiene una estética **Dark Cyber Minimal**, coherente con la identidad de [adriangvc.com](https://adriangvc.com).  
El logo y los materiales visuales están disponibles en `/media`.

> ⚡ Diseño minimalista · Profesional · Enfocado al aprendizaje práctico

---

## ⭐ Cómo contribuir

Si quieres aportar escenarios o mejorar el contenido:

1. **Haz un fork** del repositorio.  
2. Añade tu escenario siguiendo la plantilla.  
3. Crea un **pull request** con una breve descripción de tu caso.  

Toda contribución que mantenga el estándar educativo y técnico será revisada y, si procede, añadida a la colección oficial de VolatixLab.

---

## 🧩 Créditos

Este proyecto fue diseñado, estructurado y mantenido por **Adrián Gómez-Valadés Castaño**.  
Inspirado en la idea de crear un repositorio **de escenarios forenses en español**, accesible y de calidad para toda la comunidad de ciberseguridad.

---
