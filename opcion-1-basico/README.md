# Opción 1: Asistente Básico

## 🎯 ¿Qué es esto?

Un asistente de IA que:
- ✅ Funciona **100% sin internet** (offline)
- ✅ Recuerda todo lo que le preguntas
- ✅ Mejora cada día con lo que le pides
- ✅ Se ejecuta en tu terminal (línea de comandos)
- ✅ Totalmente **gratis** y local

## 🚀 Instalación Rápida (5 minutos)

### Paso 1: Instalar Python
Descarga e instala Python desde: https://www.python.org/downloads/
- Elige la versión **3.9 o superior**
- Importante: ✅ Marca la opción **"Add Python to PATH"**

### Paso 2: Instalar dependencias
Abre la terminal y ejecuta:

```bash
cd opcion-1-basico
pip install -r requirements.txt
```

**Nota:** La primera vez descargará un modelo de IA (~2 GB). Esto tarda 10-15 minutos pero solo ocurre UNA VEZ.

### Paso 3: Ejecutar el asistente
```bash
python assistant.py
```

## 💬 Cómo usar

Una vez que ejecutes `python assistant.py`:

```
=====================================
  🤖 ASISTENTE DE IA - OPCIÓN 1
=====================================

¿Cuál es tu nombre?
> Juan

¡Hola Juan! Soy tu asistente personal.
Recuerdaré todo lo que me preguntes.
(Escribe 'salir' para terminar)

Tú: ¿Cuál es la capital de Francia?
Asistente: La capital de Francia es París. Es conocida como la "Ciudad de la Luz"...

Tú: ¿Y cuál es su población?
Asistente: París tiene aproximadamente 2.2 millones de habitantes en la ciudad...

Tú: salir
Guardando memoria... ✅
¡Hasta luego Juan!
```

## 📁 Archivos importantes

| Archivo | Función |
|---------|---------|
| `assistant.py` | Código principal del asistente |
| `memoria.json` | Donde guarda tus preguntas (se crea automáticamente) |
| `requirements.txt` | Librerías necesarias |
| `README.md` | Este archivo |

## 🧠 ¿Cómo aprende?

1. **Primera conversación:** Te pedirá tu nombre y guardaré tus preferencias
2. **Cada pregunta:** Se guarda en `memoria.json`
3. **Siguiente ejecución:** Recuerda que hablamos antes y adapta respuestas
4. **Mejora constante:** Cada día aprende más sobre ti

Ejemplo de `memoria.json`:
```json
{
  "usuario": "Juan",
  "fecha_creacion": "2026-06-02",
  "conversaciones": [
    {
      "pregunta": "¿Cuál es la capital de Francia?",
      "respuesta": "La capital de Francia es París...",
      "fecha": "2026-06-02 10:30:45",
      "satisfacción": "buena"
    }
  ],
  "preferencias": {
    "respuestas_largas": true,
    "idioma": "español"
  }
}
```

## ⚙️ Características

- 🧠 **IA Local** - Modelo de lenguaje descargado en tu PC
- 💾 **Memoria Persistente** - Recuerda entre sesiones
- 🔒 **Privado** - Nada sale de tu computadora
- ⚡ **Rápido** - Respuestas instantáneas
- 🎓 **Aprende** - Se mejora cada día
- 🌍 **Offline** - Sin conexión a internet

## 🐛 Solucionar problemas

### Problema: "ModuleNotFoundError"
**Solución:** Ejecuta `pip install -r requirements.txt`

### Problema: El modelo no se descarga
**Solución:** Necesitas conexión internet la PRIMERA VEZ. Después, offline siempre.

### Problema: Respuestas lentas
**Solución:** Normal en la primera ejecución. Es CPU-intensivo. Mejora con equipos más potentes.

### Problema: "Python no es reconocido"
**Solución:** Reinstala Python y marca "Add to PATH" durante la instalación.

## 📈 Próximos pasos

Una vez domines Opción 1, puedes:
- Pasar a **Opción 2** - Agregar interfaz web
- Pasar a **Opción 3** - Dashboard de análisis
- Pasar a **Opción 4** - Desplegar en nube

## 💡 Tips para principiantes

1. **Sé específico** - Pregunta clara = respuesta mejor
2. **Haz seguimiento** - Si no entiende, reformula
3. **Valida respuestas** - Di si fue útil o no (aprende contigo)
4. **Usa regularmente** - Mejora cuanto más lo uses

---

**¿Listo para empezar? Ejecuta:**
```bash
python assistant.py
```

¿Preguntas? Revisa los logs en `debug.log`

Hecho con ❤️ para principiantes
