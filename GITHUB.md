# Cómo subir este proyecto a GitHub

## 1. Archivos listos para subir

En esta carpeta tienes ya los tres archivos listos:

- **`index.html`** — aplicación completa (movimientos, inversiones inmobiliarias con ROI/ROCE/capital invertido/total compra, opciones de inversión, resumen mensual).
- **`README.md`** — descripción del proyecto.
- **`.gitignore`** — exclusiones para Git.

## 2. Inicializar Git y primer commit

Abre una terminal en la carpeta del proyecto (`C:\Users\bersh\finanzas-personales`) y ejecuta:

```bash
git init
git add .
git commit -m "Initial commit: panel finanzas personales"
```

## 3. Crear el repositorio en GitHub

1. Entra en [github.com](https://github.com) y haz clic en **New repository**.
2. Nombre sugerido: **finanzas-personales** (o el que prefieras).
3. No marques "Add a README" (ya tienes uno en la carpeta).
4. Crea el repositorio.

## 4. Conectar y subir

En la misma terminal, sustituye `TU_USUARIO` por tu usuario de GitHub:

```bash
git remote add origin https://github.com/TU_USUARIO/finanzas-personales.git
git branch -M main
git push -u origin main
```

Si GitHub te pide autenticación, usa tu usuario y un **Personal Access Token** (no la contraseña).

## 5. Activar GitHub Pages (opcional)

Para publicar la app en la web:

1. En el repositorio de GitHub: **Settings** → **Pages**.
2. **Source:** Deploy from a branch.
3. **Branch:** `main` (o `master`) → carpeta **/ (root)**.
4. Guardar.

En unos minutos la app estará en:  
`https://TU_USUARIO.github.io/finanzas-personales/`
