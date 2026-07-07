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

El sistema usa la IA de **Groq** (modelo LLaMA 3.1). La API key **no** está en el código: se guarda en tu navegador.

1. Conseguí una API key gratis en https://console.groq.com/keys (empieza con `gsk_`)
2. Abrí la página del sistema
3. Hacé clic en **🔑 API Key** en el menú lateral
4. Pegá la key y aceptá — queda guardada en ese navegador

⚠️ **Importante:** nunca pegues la API key dentro del código en GitHub. Como el repositorio es público, GitHub y Groq la detectan y la revocan automáticamente en minutos (por eso dejaba de funcionar). Guardándola desde el botón 🔑 no se publica nunca.

## 📋 Formato de ficha generada

- Header técnico (nombre, especialidad, experiencia, tecnologías)
- Matriz de fortalezas (Hard & Soft Skills)
- Resumen ejecutivo con Market-Fit
- Guía de entrevista personalizada
- Bitácora para llenar en entrevista

## 💾 Almacenamiento

Los candidatos se guardan en la nube (Firebase), así se ven desde cualquier dispositivo. También podés exportar todo a Excel desde la Biblioteca de Talentos.

## ⚠️ Notas

- La API de Groq tiene un plan gratuito (modelo usado: LLaMA 3.1 8B)
- Podés subir PDFs o pegar el texto del CV
- La API key se guarda solo en tu navegador; si cambiás de computadora o navegador, volvé a pegarla con el botón 🔑
