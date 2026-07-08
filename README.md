# Tienda San Martín — Demo estática

Sistema web de demostración para el proyecto de Interacción Humano-Computador.

## Incluye

- Login simulado.
- Dashboard con indicadores.
- Registro de ventas con carrito y cálculo automático.
- Gestión de productos.
- Reabastecimiento de stock.
- Reportes de ventas, ranking e inventario.
- Configuración simulada.
- Panel de accesibilidad.
- Responsive Design con Bootstrap y CSS.
- Sin base de datos.

Los datos se manejan en JavaScript y se guardan en `localStorage` del navegador.

## Credenciales

- Usuario: `admin`
- Contraseña: `1234`

## Ejecutar en Visual Studio Code

1. Abre la carpeta en VS Code.
2. Instala la extensión **Live Server**.
3. Haz clic derecho sobre `index.html`.
4. Selecciona **Open with Live Server**.

También puedes abrir `index.html` directamente con doble clic.

## Subir a GitHub

```bash
git init
git add .
git commit -m "Primera versión demo Tienda San Martín"
git branch -M main
git remote add origin TU_URL_DEL_REPOSITORIO
git push -u origin main
```

## Publicar con GitHub Pages

1. Sube el proyecto a un repositorio.
2. Ve a **Settings > Pages**.
3. En **Build and deployment**, elige **Deploy from a branch**.
4. Selecciona la rama `main` y la carpeta `/root`.
5. Guarda.
