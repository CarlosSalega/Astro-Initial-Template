# 🚀 Astro Initial Template

Un template inicial para proyectos basados en [Astro](https://astro.build/), diseñado para proporcionar una base sencilla y eficiente que puedes clonar y empezar a usar de inmediato.

## 🌟 Características

- **Astro 4.x**: Framework moderno y rápido para sitios web estáticos y multipáginas.
- **Tailwind CSS**: Estilización rápida y flexible.
- **Astro Icon**: Fácil integración de íconos SVG.
- **TypeScript**: Configurado y listo para usar.
- **Prettier**: Formato de código consistente, con soporte para Astro y Tailwind CSS.

---

## 📂 Estructura del Proyecto

```plaintext
astro-initial-template/
├── public/               # Archivos estáticos (favicon, imágenes, etc.)
├── src/                  # Código fuente
│   ├── components/       # Componentes reutilizables
│   ├── layouts/          # Layouts para las páginas
│   ├── pages/            # Páginas principales del sitio
│   ├── styles/           # Estilos globales (Tailwind incluido)
│   └── data/             # Datos estáticos o mock
├── package.json          # Dependencias y scripts
├── astro.config.mjs      # Configuración de Astro
├── tsconfig.json         # Configuración de TypeScript
└── README.md             # Este archivo
```

## 🛠️ Requisitos Previos

Node.js 16.15.0 o superior
npm (o un gestor de paquetes como Yarn o pnpm)

## 🚀 Cómo Usar Este Template

1️⃣ Clonar el Repositorio
bash
Copiar código
git clone https://github.com/tu-usuario/astro-initial-template.git
cd astro-initial-template
2️⃣ Instalar Dependencias
bash
Copiar código
npm install
3️⃣ Iniciar el Servidor de Desarrollo
bash
Copiar código
npm run dev
Abre http://localhost:3000 en tu navegador para ver el proyecto en acción.

## 📦 Scripts Disponibles

npm run dev: Inicia el servidor de desarrollo.
npm run build: Construye la aplicación para producción.
npm run preview: Sirve la aplicación construida localmente.
npm run astro: Acceso directo al CLI de Astro.

## ⚙️ Dependencias Clave

Astro: Framework principal.
Tailwind CSS: Utilidades de CSS para un diseño ágil.
Astro Icon: Íconos fáciles de usar en Astro.
TypeScript: Tipado estático opcional para JavaScript.

## 🔧 Herramientas para Desarrollo

Prettier: Formato de código.
Prettier Plugin Astro: Soporte para archivos .astro.
Prettier Plugin Tailwind CSS: Ordena automáticamente las clases de Tailwind.

## ✨ Personalización

Actualizar Metaetiquetas: Cambia el título, descripción y favicon en src/pages/index.astro y el directorio public/.
Estilización: Agrega tus estilos globales o personaliza Tailwind CSS en src/styles/global.css.

## 🧑‍💻 Contribuciones

¡Si tienes sugerencias o mejoras, siéntete libre de abrir un issue o enviar un pull request!

## 📄 Licencia

Este proyecto está bajo la licencia MIT.
