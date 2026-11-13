<div align="center">

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg?style=for-the-badge)](https://github.com/ale-ratalife/Team-Dev-Pro-Clade-Skill-)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Powered by](https://img.shields.io/badge/Powered_by-Alex_%26_Alex_Software_and_Innovation-black.svg?style=for-the-badge)](https://alexyalex.site)
[![Author](https://img.shields.io/badge/Author-V._Alejandro_Téllez-purple.svg?style=for-the-badge)](https://github.com/ale-ratalife)

# 🚀 Team Dev Pro - Multi-Agent Skill

**Una arquitectura de ingeniería de software de alto rendimiento simulada para Modelos de Lenguaje (Claude / Gemini).**

</div>

---

## 📌 ¿Qué es Team Dev Pro?

Team Dev Pro no es un simple prompt, es una **arquitectura multi-agente** empaquetada como un Skill. Su objetivo es forzar a la IA a comportarse como un equipo completo de 9 ingenieros de software, eliminando divagaciones, preguntas innecesarias y entregando código nivel producción de forma inmediata.

Desarrollado y optimizado por [Alex & Alex Software and Innovation](https://alexyalex.site).

## ⚙️ ¿Cómo Funciona?

El Skill utiliza un **Pipeline de Triage Inteligente**. Cuando inicias un prompt con la palabra clave `Team:`:

1. **Bypass de Emergencia:** Si la petición es trivial (ej. "dime la hora", "resume este texto en 2 líneas"), el equipo se ignora y la IA responde directo para no gastar tokens ni tiempo.
2. **Full Pipeline:** Si es una tarea compleja de código o arquitectura, el sistema asume 9 roles en cadena silenciosa:
   - 👔 **PO (Product Owner):** Define requerimientos clave.
   - 🏗️ **Lead Architect:** Diseña la arquitectura global y stack.
   - 🗄️ **DBA:** Estructura modelos y queries.
   - 🚀 **DevOps:** Prepara Docker y configs.
   - ⚙️ **Backend:** Escribe la lógica fuerte.
   - 🎨 **Frontend:** Pule la interfaz gráfica.
   - 🔒 **SecOps:** Tapona vulnerabilidades.
   - 🧪 **QA:** Mete lógica defensiva.
   - 👁️ **Code Reviewer:** Ensambla, limpia de comentarios basura y te entrega el producto final.

Todo el texto generado está filtrado por directrices *Strict Output* (Cero saludos, cero intros, directo al grano).

## 🛠️ Instalación y Uso (GitHub)

Para integrar este Skill en tu entorno, clona el repositorio directamente:

```bash
git clone https://github.com/ale-ratalife/Team-Dev-Pro-Clade-Skill-.git
```

### Configuración Manual
1. Descarga el repositorio.
2. Copia el contenido de `SKILL.md` como tu prompt maestro.
3. Asegúrate de adjuntar en tu base de conocimiento o contexto del agente los archivos de las carpetas `protocols/`, `roles/` y `guidelines/` para que las reglas estrictas se apliquen.
4. **Uso:** Simplemente escribe `Team: crea un SaaS en Next.js` en tu chat.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---
*Hecho con ⚡ por [Alex & Alex Software and Innovation](https://alexyalex.site).*
