# Portafolio

Base de portafolio para mostrar proyectos de programacion de videojuegos con Unity y C#.

## Estructura

- `index.html`: contenido de la pagina.
- `style.css`: colores, layout y estilos visuales.
- `assets/images/`: imagenes, capturas y GIFs del portafolio.

## Como editar proyectos

En `index.html`, busca la seccion `Proyectos destacados`. Cada proyecto esta dentro de un bloque:

```html
<article class="project-card">
```

Cambia el titulo, la descripcion, las tecnologias y los links.

Para usar una imagen o GIF, reemplaza el bloque `placeholder-media` por:

```html
<img class="project-media" src="assets/images/mi-demo.gif" alt="Demo del proyecto">
```

Para usar un video local:

```html
<video class="project-media" controls>
    <source src="assets/videos/demo.mp4" type="video/mp4">
</video>
```

Para publicar cambios:

```powershell
git add .
git commit -m "Actualizar portafolio"
git push origin main
```
