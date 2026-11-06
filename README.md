# Flip 7 — Planilla de Puntuación y Evolución (Web + PWA + APK)

Este repositorio está listo para desplegarse gratis en **Render** o **GitHub Pages** y convertirse en una aplicación **APK** para Android.

## 1. Subir a GitHub
1. Crea un repositorio nuevo en [GitHub](https://github.com/new).
2. Sube todos los archivos de esta carpeta (`index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`, `render.yaml`, `package.json`, `capacitor.config.json`).

## 2. Publicar en Render (Gratis)
1. Entra a [Render](https://dashboard.render.com/) → **New +** → **Static Site**.
2. Conecta tu repositorio de GitHub.
3. En **Build Command** déjalo vacío y en **Publish Directory** escribe `.` (un punto).
4. Haz clic en **Create Static Site** y en segundos tendrás tu URL pública (`https://tu-app.onrender.com`).

## 3. Instalar como App / Generar el archivo .APK para el teléfono
* **Opción A (Directo sin bajar APK):** Abre la URL de Render en Chrome desde tu teléfono Android y toca el botón **📲 Instalar App** arriba a la derecha (o en el menú `⋮` de Chrome elige **Instalar aplicación**). Se instalará en tu pantalla de inicio a pantalla completa y funcionará incluso sin internet.
* **Opción B (Descargar archivo `.apk` instalable):** Entra a [PWABuilder.com](https://www.pwabuilder.com/), pega tu URL de Render, haz clic en **Start** → **Package for stores** → en **Android** elige **Download Package** y tendrás el archivo `.apk` listo para pasar por WhatsApp o instalar en cualquier Android.
