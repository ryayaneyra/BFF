# Flores Amarillas · 21 de Setiembre

Experiencia web interactiva (mobile-first) para celebrar el 21 de setiembre con cinco compañeros docentes: Jamir, Leidy, Nicole, Rosalinda y Jennifer.

Sitio estático: HTML, CSS y JavaScript en un solo archivo (`index.html`), sin dependencias ni proceso de compilación.

## Estructura

```
flores-amarillas/
├── index.html     # Toda la experiencia
├── favicon.svg    # Ícono de la pestaña
├── vercel.json    # Configuración de Vercel
├── .gitignore
└── README.md
```

## Ver en local

Abre `index.html` directamente en el navegador.

## Subir a GitHub

```bash
cd flores-amarillas
git init
git add .
git commit -m "Flores Amarillas: primera versión"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/flores-amarillas.git
git push -u origin main
```

## Desplegar en Vercel

1. Entra a https://vercel.com e inicia sesión con tu cuenta de GitHub.
2. Pulsa **Add New… → Project** e importa el repositorio `flores-amarillas`.
3. En **Framework Preset** elige **Other**. Deja vacíos Build Command y Output Directory.
4. Pulsa **Deploy**. En unos segundos tendrás un enlace como `flores-amarillas.vercel.app`.

Cada vez que hagas `git push` a `main`, Vercel vuelve a publicar automáticamente.

---
Investigando para Educar
