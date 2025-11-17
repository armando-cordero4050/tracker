# Tracker Monorepo

Este repositorio contiene la distribución de Vuexy Admin (`vuexy-admin-v9.4.0`) con ejemplos para múltiples stacks: ASP.NET Core, React (Vite/Next.js) y Vue (Vuetify). Usa la documentación incluida en cada subcarpeta y esta guía rápida para arrancar proyectos típicos.

## Requisitos
- Node.js LTS y npm (o yarn/pnpm)
- .NET SDK (6+ recomendado) para los proyectos ASP.NET Core
- Git

Verifica versiones:
```powershell
node -v
npm -v
dotnet --info
```

## Estructura principal
- `vuexy-admin-v9.4.0/aspnet-core/`
  - `AspnetCoreFull/` y `AspnetCoreStarter/`
  - `documentation.html` con pasos detallados
- `vuexy-admin-v9.4.0/react-version/`
  - `vite-bootstrap5/` (full-version, starter-kit)
  - `nextjs-mui/` (javascript-version, typescript-version)
- `vuexy-admin-v9.4.0/vue-version/`
  - `vuexy-vuetify-vue3/` (javascript-version, typescript-version)

Cada stack incluye su propia documentación (`documentation.html`).

## Inicios rápidos

### ASP.NET Core (ejemplo)
```powershell
# Opción 1: CLI .NET
Set-Location "vuexy-admin-v9.4.0/aspnet-core/AspnetCoreFull"
dotnet restore
# Si el proyecto usa assets con Node/Gulp/Webpack, instala dependencias
if (Test-Path package.json) { npm install }
# Ejecutar
DotNet build
DotNet run

# Opción 2: Visual Studio / Rider
# Abre la solución .sln y ejecuta el proyecto de inicio.
```

### React – Vite (starter kit)
```powershell
Set-Location "vuexy-admin-v9.4.0/react-version/vite-bootstrap5/starter-kit"
npm install
npm run dev
```

### React – Next.js MUI (JS)
```powershell
Set-Location "vuexy-admin-v9.4.0/react-version/nextjs-mui/javascript-version"
npm install
npm run dev
```

### Vue 3 – Vuetify (JS)
```powershell
Set-Location "vuexy-admin-v9.4.0/vue-version/vuexy-vuetify-vue3/javascript-version"
npm install
npm run dev
```

> Nota: Revisa el `README.md`/`documentation.html` de cada subproyecto para comandos exactos, scripts disponibles y variables de entorno.

## Estilo y Git
- `.editorconfig` en la raíz define indentación y finales de línea consistentes (CRLF, espacios; C# a 4 espacios, JS/TS a 2).
- `.gitignore` ignora `node_modules/`, artefactos de build (`dist/`, `build/`, `.next/`, `.nuxt/`), binarios de .NET (`bin/`, `obj/`), logs y archivos de entorno (`.env*`). Mantén plantillas como `*.example` versionadas.

## Troubleshooting
- Si faltan dependencias: `npm install` o `dotnet restore` en la carpeta del proyecto.
- Si hay problemas de permisos en Windows: ejecuta la terminal como Administrador.
- Si el dev server ya usa el puerto, cambia el puerto con flags del script (`--port`) o variables de entorno.
