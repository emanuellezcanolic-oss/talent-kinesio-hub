# 🏥 Talent Kinesio Hub

Sistema de evaluación de CVs con IA para centros de Kinesiología y Entrenamiento.

## 🚀 Cómo usar

1. **Subir a GitHub:**
   - Crea un repositorio nuevo
   - Sube el archivo `index.html`
   - Activa GitHub Pages (Settings > Pages > Branch: main)

2. **Usar el sistema:**
   - Abre la URL de GitHub Pages
   - Pega el texto del CV del candidato
   - Selecciona el tipo de perfil (opcional)
   - Haz clic en "Analizar CV con IA"

3. **Guardar candidatos:**
   - Los perfiles se guardan automáticamente en el navegador
   - Puedes copiar la ficha o exportarla

## 🔧 Configuración de la API

La API key de OpenRouter ya está configurada. Si quieres cambiarla:
- Edita la línea `const API_KEY = 'tu-api-key'` en el archivo

## 📋 Formato de ficha generada

- Header técnico (nombre, especialidad, experiencia, tecnologías)
- Matriz de fortalezas (Hard & Soft Skills)
- Resumen ejecutivo con Market-Fit
- Guía de entrevista personalizada
- Bitácora para llenar en entrevista

## 💾 Almacenamiento

Los datos se guardan en el `localStorage` del navegador. Para exportar:
- Abre las herramientas de desarrollador (F12)
- Console: `copy(localStorage.getItem('kinesioCandidates'))`

## ⚠️ Notas

- La API de OpenRouter requiere créditos (modelo usado: GPT-3.5-turbo)
- Los CVs deben estar en texto plano
- Los datos se guardan localmente, no en servidor
