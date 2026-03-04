# Panel de finanzas personales

Aplicación web para gestionar ingresos, gastos, inversiones inmobiliarias y seguimiento de préstamos/hipotecas. Todo funciona en el navegador con almacenamiento local (sin servidor).

## Características

- **Movimientos**: registro de ingresos y gastos con categorías, etiquetas, filtros por año/mes y gráficos por categoría.
- **Inversiones inmobiliarias**: alta de pisos con total compra, capital invertido, ROI (%), ROCE (%), renta mensual; y por cada uno, control mensual de cobro de renta (checkbox) y archivo de pago por mes.
- **Opciones de inversión**: TAE, años, préstamo solicitado, cuota mensual y desglose anual de intereses/amortización (actualizable una vez al año).
- **Resumen por mes**: vista rápida de ingresos, gastos por categoría y % de ahorro de cada mes del año.

## Estructura del repositorio

- `index.html` — aplicación (página principal), con movimientos, inversiones inmobiliarias (ROI, ROCE, capital invertido, total compra), opciones de inversión y resumen mensual.
- `README.md` — este archivo.
- `GITHUB.md` — pasos para subir el proyecto a GitHub y activar GitHub Pages.

## Cómo usar

1. Abre `index.html` en tu navegador (doble clic o arrastra el archivo al navegador).
2. Los datos se guardan automáticamente en el **localStorage** de tu navegador (no se envían a ningún servidor).
3. Puedes exportar ingresos y gastos a CSV desde el panel de Movimientos.

## Requisitos

Solo un navegador moderno (Chrome, Firefox, Edge, Safari). No hace falta instalar nada.

## Publicar en GitHub Pages

1. Sube este repositorio a GitHub.
2. En el repositorio: **Settings** → **Pages**.
3. En **Source** elige **Deploy from a branch**.
4. Branch: **main** (o **master**), carpeta **/ (root)**.
5. Guarda. En unos minutos la app estará en `https://tu-usuario.github.io/finanzas-personales/`.

> **Nota**: En GitHub Pages los datos seguirán guardándose en el localStorage del navegador de cada visitante; no se almacenan en GitHub.

## Licencia

Uso libre para uso personal y educativo.
