# 🔗 Generador de Códigos QR

Un generador de códigos QR moderno, responsive y multilingüe construido con React y Vite. Genera códigos QR para URLs, texto libre e información de contacto (vCard) de forma instantánea.

## ✨ Características

- 🌐 **Multilingüe**: Soporte para español e inglés con detección automática
- 📱 **Responsive**: Diseño adaptativo que funciona en móvil, tablet y desktop
- 🎨 **Interfaz Moderna**: UI elegante con gradientes y animaciones suaves
- 🔗 **Múltiples Tipos**: URLs, texto libre y tarjetas de contacto vCard
- 💾 **Descarga Directa**: Descarga códigos QR como imágenes PNG
- 📋 **Copiar Datos**: Copia el contenido del QR al portapapeles
- 🚀 **Sin Backend**: Funciona completamente en el cliente
- 🔒 **Privacidad**: No se almacenan datos, todo es procesado localmente

## 🖥️ Demo en Vivo

Visita la demo en: [https://juanjo6358.github.io/qr-code-generator](https://juanjo6358.github.io/qr-code-generator)

## 🚀 Inicio Rápido

### Prerrequisitos

- Node.js (versión 14 o superior)
- npm o yarn

### Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/juanjo6358/qr-code-generator.git
cd qr-code-generator
```

2. Instala las dependencias:
```bash
npm install
```

3. Inicia el servidor de desarrollo:
```bash
npm run dev
```

4. Abre tu navegador en `http://localhost:5173`

## 🏗️ Construcción para Producción

```bash
# Construir la aplicación
npm run build

# Vista previa de la construcción
npm run preview

# Desplegar a GitHub Pages
npm run deploy
```

## 📱 Uso

### 1. URLs
- Ingresa cualquier URL válida
- Se agrega automáticamente `https://` si no se especifica el protocolo
- Genera un QR que redirige al sitio web

### 2. Texto Libre
- Escribe cualquier texto personalizado
- Ideal para mensajes, notas o información breve
- Sin límites de caracteres (aunque QRs muy largos pueden ser difíciles de escanear)

### 3. Información de Contacto
- Genera tarjetas vCard compatibles con la mayoría de dispositivos
- Campos disponibles:
  - Nombre y apellido
  - Teléfono
  - Email
  - Organización/Empresa
  - Sitio web

### 4. Funciones Adicionales
- **Descargar**: Guarda el código QR como imagen PNG
- **Copiar Datos**: Copia el contenido al portapapeles
- **Limpiar Campos**: Resetea todos los formularios

## 🛠️ Tecnologías Utilizadas

- **React 18** - Framework de UI
- **Vite** - Build tool y dev server
- **Tailwind CSS** - Framework de CSS utility-first
- **Lucide React** - Iconos SVG
- **QRious** - Generación de códigos QR
- **GitHub Pages** - Hosting gratuito

## 📁 Estructura del Proyecto

```
qr-code-generator/
├── public/
│   └── vite.svg
├── src/
│   ├── components/
│   │   └── QRCodeGenerator.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── index.html
├── package.json
├── vite.config.js
├── tailwind.config.js
├── postcss.config.js
├── .gitignore
└── README.md
```

## 🌍 Internacionalización

La aplicación detecta automáticamente el idioma del navegador y soporta:

- **Español (es-ES)** - Idioma principal
- **Inglés (en-US)** - Idioma de respaldo

Los textos se gestionan mediante un objeto de traducciones centralizado.

## 📦 Despliegue en GitHub Pages

### Configuración automática:

1. El proyecto ya está configurado para GitHub Pages
2. Ejecuta `npm run deploy` para desplegar automáticamente

### Configuración manual:

1. Ve a tu repositorio en GitHub
2. Settings → Pages
3. Source: Deploy from a branch
4. Branch: gh-pages
5. Folder: / (root)

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Sigue estos pasos:

1. Fork el proyecto
2. Crea tu rama de características (`git checkout -b feature/nueva-caracteristica`)
3. Commit tus cambios (`git commit -m 'Añadir nueva característica'`)
4. Push a la rama (`git push origin feature/nueva-caracteristica`)
5. Abre un Pull Request

### Ideas para Contribuir

- 🌐 Añadir más idiomas
- 🎨 Nuevos temas de color
- 📊 Soporte para códigos QR de datos estructurados (WiFi, SMS, etc.)
- 📱 Mejoras en la experiencia móvil
- 🔧 Optimizaciones de rendimiento

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 👤 Autor

**Juan José**
- GitHub: [@juanjo6358](https://github.com/juanjo6358)
- Proyecto: [qr-code-generator](https://github.com/juanjo6358/qr-code-generator)

## 🙏 Agradecimientos

- [QRious](https://github.com/neocotic/qrious) - Librería para generación de códigos QR
- [Lucide](https://lucide.dev/) - Iconos SVG hermosos y consistentes
- [Tailwind CSS](https://tailwindcss.com/) - Framework CSS utility-first
- [Vite](https://vitejs.dev/) - Build tool rápido y moderno

---

⭐ ¡Dale una estrella a este repositorio si te resultó útil!

## 🐛 Reportar Problemas

¿Encontraste un bug o tienes una sugerencia? 

[Abrir un Issue](https://github.com/juanjo6358/qr-code-generator/issues/new)

---

Hecho con ❤️ por [Juan José](https://github.com/juanjo6358)