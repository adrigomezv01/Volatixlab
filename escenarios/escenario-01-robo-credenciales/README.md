# 🧩 Escenario 01 – Robo de credenciales corporativas

## 📖 Descripción general
El departamento de soporte técnico ha detectado actividad sospechosa en un equipo corporativo con Windows 10.  
El usuario afectado reportó que su sesión se cerró repentinamente y algunos correos fueron enviados sin su consentimiento.  

Se han extraído un **volcado de memoria (RAM)** y una **imagen del disco** del equipo comprometido para su análisis.

> 🧠 Tu objetivo será determinar si se produjo un robo de credenciales, cómo ocurrió y qué evidencias lo confirman.

---

## 🎯 Objetivos del análisis
- Identificar procesos o conexiones sospechosas en memoria.  
- Localizar posibles credenciales almacenadas o exfiltradas.  
- Analizar persistencia o malware presente.  
- Reconstruir la secuencia del ataque.

---

## 💾 Evidencias incluidas
| Tipo | Archivo | Descripción |
|------|----------|-------------|
| Memoria RAM | `memoria.raw` | Volcado de memoria del equipo afectado |
| Disco | `disco.vhd` | Imagen de disco completa |

> 📁 Archivos disponibles en la carpeta `/evidencias/` (se incluirán más adelante).

---

## 🔍 Herramientas recomendadas
- Volatility 3  
- Autopsy  
- FTK Imager  
- RegRipper  
- Wireshark  

---

## 🧠 Pistas iniciales
> 💡 Se sospecha que un proceso malicioso se estaba ejecutando en segundo plano durante el robo.  
> 💡 Podría haberse usado una herramienta tipo “Mimikatz” para extraer contraseñas.  
> 💡 El atacante podría haber mantenido una conexión remota activa antes de exfiltrar credenciales.

---

## 🕵️‍♂️ Preguntas de investigación
1. ¿Qué proceso o archivo originó el robo de credenciales?  
2. ¿Qué usuario o cuenta fue comprometida?  
3. ¿Existen evidencias de Mimikatz u otras herramientas de extracción de contraseñas?  
4. ¿Qué conexiones de red se observaron durante el ataque?  
5. ¿Qué indicios hay en el registro o disco del atacante?

---

## 🧾 Solución
Si necesitas apoyo o referencia, consulta `/solucion/writeup.md`  
(este documento contendrá un análisis técnico completo paso a paso).

---

## 👤 Autor
**Adrián Gómez-Valadés Castaño**  
📍 Don Benito / Badajoz  
🌐 [adriangvc.com](https://adriangvc.com)
🧠 Proyecto: [VolatixLab](https://github.com/adrigomezv01/VolatixLab)

---
