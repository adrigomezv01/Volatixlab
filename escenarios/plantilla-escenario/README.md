 # 🧩 Escenario X – [Título del caso]

## 📖 Descripción general
Breve introducción del caso: contexto, entorno y posible incidente.

> 🧠 Ejemplo:  
> Se ha detectado actividad sospechosa en un equipo Windows del departamento de contabilidad.  
> El usuario reportó pérdida de acceso a su cuenta de correo y comportamiento anómalo en el sistema.

---

## 🎯 Objetivos del análisis
- Identificar la causa del incidente.  
- Localizar las evidencias clave.  
- Determinar si hubo exfiltración o robo de datos.  
- Redactar un informe técnico.

---

## 💾 Evidencias incluidas
| Tipo | Archivo | Descripción |
|------|----------|-------------|
| Memoria RAM | `memoria.raw` | Volcado de memoria del sistema afectado. |
| Disco | `disco.vhd` | Imagen completa del disco duro. |
| Otros | — | — |

> 📁 Todas las evidencias se encuentran en la carpeta `/evidencias/`.

---

## 🔍 Herramientas recomendadas
- Volatility 3  
- Autopsy  
- FTK Imager  
- HxD / Strings  
- Wireshark  

---

## 🧠 Pistas iniciales
> 💡 Ejemplo de pistas:  
> - Un proceso inusual se ejecuta en segundo plano.  
> - Puede haber una conexión remota activa.  
> - El volcado de memoria podría contener contraseñas en texto plano.  

---

## 🕵️‍♂️ Preguntas de investigación
1. ¿Qué procesos sospechosos aparecen en la memoria?  
2. ¿Qué usuario inició sesión durante el incidente?  
3. ¿Existen evidencias de robo de credenciales?  
4. ¿Se descargaron o ejecutaron binarios desconocidos?  
5. ¿Qué eventos en el registro o archivos de log son relevantes?  

---

## 🧾 Solución (opcional)
Si el escenario incluye una resolución detallada, estará en:  
`/solucion/writeup.md`

---

## 🧩 Información técnica
| Campo | Valor |
|--------|--------|
| Sistema operativo | Windows 10 x64 |
| Fecha de captura | 2025-11-04 |
| Tamaño de evidencia RAM | 2 GB |
| Tamaño de evidencia Disco | 10 GB |

---

## 👤 Autor del escenario
- **Nombre:** Adrián Gómez-Valadés Castaño  
- **Proyecto:** [VolatixLab](https://github.com/adrigomezv01/VolatixLab)  
- **Web:** [adriangvc.com](https://adriangvc.com)

---

> ⚙️ Usa esta plantilla para todos los nuevos casos que subas al repositorio VolatixLab.
> Sustituye los valores entre corchetes y añade los datos reales de tu escenario.

