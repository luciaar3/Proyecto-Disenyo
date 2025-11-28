# Sass — Guía de Instalación y Uso

## 📌 ¿Qué es Sass?
**Sass** (Syntactically Awesome StyleSheets) es un preprocesador de CSS que permite escribir estilos de forma más clara, reutilizable y potente. Luego se compila a CSS tradicional para ser entendido por el navegador.

---

## 🚀 Instalación de Sass (Dart Sass)

La forma recomendada de instalar Sass hoy en día es usando **npm**, que viene incluido con Node.js.

### ✅ 1. Instalar Sass de forma global

Asegúrate de tener **Node.js** instalado. Luego ejecuta:

```bash
npm install -g sass
```

## 🔄 Usar Sass con el comando --watch

El comando `--watch` permite que Sass compile automáticamente tus archivos `.scss` cada vez que detecta un cambio.

### ▶ Watch para un solo archivo

```bash
sass --watch ./scss/main.scss:./css/main.css
```