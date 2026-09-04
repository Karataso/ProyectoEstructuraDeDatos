# Estructuras de Datos — Proyectos Multimedia Interactivos

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

Colección de objetos multimedia interactivos para estudiar estructuras de datos fundamentales, desarrollada como proyecto académico. Cada módulo permite manipular la estructura en tiempo real con retroalimentación visual inmediata.

**Ver demo:** [karataso.github.io/ProyectoEstructuraDeDatos](https://karataso.github.io/ProyectoEstructuraDeDatos/)

## Módulos

| Módulo | Descripción | Recurso |
|---|---|---|
| **Colas** | Estructura FIFO con colas normales y circulares, soporte para modos FIFO/LIFO, iteradores Frente y Final y manejo de desbordamientos | [`Colas/Colas.html`](Colas/Colas.html) |
| **Pilas** | Estructura LIFO con operaciones push, pop y peek, iterador Tope dinámico y visualización vertical | [`Pilas/Pilas.html`](Pilas/Pilas.html) |
| **Árboles Binarios** | Árboles binarios de búsqueda con inserción, eliminación, búsqueda y cuatro tipos de recorrido | [`Arboles/Arboles.html`](Arboles/Arboles.html) |
| **Glosario** | Diccionario interactivo con definiciones y ejemplos de conceptos clave, con modo oscuro/claro persistente | [`Glosario/Glosario.html`](Glosario/Glosario.html) |

## Características

- **JavaScript vanilla** — sin dependencias ni frameworks externos
- **Interfaz oscura** con colores vibrantes y efectos visuales
- **Responsive** — adaptable a dispositivos de todos los tamaños
- **Interactivo** — manipulación en tiempo real de cada estructura

## Estructura del proyecto

```
.
├── index.html              # Página principal (hub de módulos)
├── Arboles/
│   └── Arboles.html
├── Colas/
│   ├── Colas.html
│   ├── script.js
│   └── style.css
├── Glosario/
│   └── Glosario.html
└── Pilas/
    └── Pilas.html
```

## Uso

Es un sitio estático publicado en GitHub Pages: basta con abrir `index.html` en el navegador, o servirlo localmente:

```bash
# con Python
python3 -m http.server 8000

# o con Node
npx serve .
```

---

Desarrollado por [Arafath Sepulveda](https://github.com/Karataso)
