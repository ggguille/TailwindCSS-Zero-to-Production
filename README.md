# TailwindCSS-Zero-to-Production

## First contact with Tailwind CSS

[tailwindcss.com](https://tailwindcss.com/)

[Playlist: Tailwind CSS: From Zero to Production](https://www.youtube.com/playlist?list=PL5f_mz_zU5eXWYDXHUDOLBE0scnuJofO0)

---

### 01 - Setting up Tailwind CSS

Using _base_, _component_ and _utilities_

**Build command** >
 `npx tailwindcss-cli build css/tailwind.css -o build/tailwind.css`

DEV dependencies

```json
"@vitejs/plugin-react-refresh": "^1.1.3",
"autoprefixer": "^10.2.5",
"postcss": "^8.2.12",
"tailwindcss": "^2.1.1",
"vite": "^2.2.1"
```

Dependencies

```json
"react": "^17.0.1",
"react-dom": "^17.0.1"
```

**Set configuration files** > `npx tailwindcss init -p`

**Run dev environment** > `npm run dev`

### 02 - The Utility-First Workflow Tailwind CSS

Build a custom design only with utility classes

### 03 - Responsive Design

Make custom design responsive

### 04 - Hover, Focus and other States

Use classes to define hover, focus and active states of the button

### 05 - Composing Utilities with @apply

Define composable classes applying utilitiy classes

### 06 - Extracting Reusable Components

Build reusable components with React styling with tailwind utilities

### 07 - Customizing Your Design System

Custom design properties

**Set full configuration file** > `npx tailwindcss init tailwind-full.config.js --full`

### 08 - Optimizing for Production

Prepare css building for production

**Build project** > `npm run build`

---

#### TOOLS

- [Vite](https://vitejs.dev/)
- [PostCSS](https://postcss.org/)
- [PurgeCSS](https://purgecss.com/)
