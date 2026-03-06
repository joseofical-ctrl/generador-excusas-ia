# 🤖 Generador de Excusas con IA

> Genera excusas creativas y divertidas para cualquier situación usando
> inteligencia artificial.

Esta es una aplicación web moderna que utiliza IA para generar excusas
de forma automática según diferentes categorías. El proyecto está
construido con tecnologías modernas del ecosistema web como **Next.js,
TypeScript y TailwindCSS**.

Este proyecto también forma parte de mi proceso de aprendizaje mientras
empiezo en el mundo del desarrollo web y la programación.

------------------------------------------------------------------------

# ✨ Características

-   🧠 Generación de excusas con IA
-   🗂️ 6 categorías diferentes
    -   Universidad
    -   Trabajo
    -   Amigos
    -   Familia
    -   Relación
    -   Absurdas
-   🌐 Soporte para dos idiomas (Inglés / Español)
-   ❤️ Sistema de favoritos
-   📋 Copiar excusas al portapapeles
-   ⌨️ Animación tipo máquina de escribir
-   🎨 Interfaz moderna con modo oscuro
-   📱 Diseño responsive
-   💾 Preferencias guardadas en localStorage
-   🎞️ Animaciones fluidas

------------------------------------------------------------------------

# 🛠️ Tecnologías utilizadas

-   Next.js
-   React
-   TypeScript
-   TailwindCSS
-   Framer Motion
-   OpenAI API
-   Node.js

------------------------------------------------------------------------

# 📦 Instalación

## Requisitos

-   Node.js v18 o superior
-   npm / yarn / pnpm
-   Una API Key de OpenAI

Puedes obtenerla aquí: https://platform.openai.com/api-keys

------------------------------------------------------------------------

## 1. Clonar el repositorio

``` bash
git clone https://github.com/tu-usuario/generador-de-excusas.git
cd generador-de-excusas
```

## 2. Instalar dependencias

``` bash
npm install
```

## 3. Crear variables de entorno

Crea un archivo:

.env.local

Y agrega tu API key:

OPENAI_API_KEY=tu_api_key_aqui

⚠️ Este archivo **no debe subirse a GitHub**.

## 4. Ejecutar el proyecto

``` bash
npm run dev
```

Luego abre:

http://localhost:3000

------------------------------------------------------------------------

# 💡 Cómo usar la aplicación

### Generar una excusa

1.  Selecciona una categoría
2.  Haz clic en **Generate Excuse**
3.  La IA generará una excusa automáticamente

### Guardar favoritos

Presiona el botón de ❤️ para guardar la excusa.

### Copiar excusa

Usa el botón **Copy** para copiar la excusa al portapapeles.

### Cambiar idioma

Puedes cambiar entre:

EN / ES

La interfaz se actualizará automáticamente.

------------------------------------------------------------------------

# 📁 Estructura del proyecto

generador-de-excusas

app/ ├ layout.tsx ├ page.tsx ├ globals.css └ api/ └ generate-excuse/

components/ ├ Header.tsx ├ CategorySelector.tsx ├ GenerateButton.tsx ├
ExcuseCard.tsx └ FavoritesList.tsx

hooks/ ├ useFavorites.ts └ useLanguage.ts

lib/ ├ openai.ts └ translations.ts

types/

------------------------------------------------------------------------

# 🚀 Posibles mejoras futuras

-   Compartir excusas en redes sociales
-   Historial de excusas generadas
-   Más idiomas
-   Diferentes estilos de excusas
-   Sistema de usuarios
-   Convertir la app en PWA

------------------------------------------------------------------------

# 👨‍💻 Autor

**José Castro**

Actualmente estoy empezando en el mundo del desarrollo y este proyecto
forma parte de mi aprendizaje mientras construyo mi **portfolio como
desarrollador**.
