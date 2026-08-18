# MonograJairo — Superhéroes de Marvel

Monografía web interactiva sobre superhéroes de Marvel, construida con HTML5, CSS3 y Bootstrap 5. El proyecto presenta a distintos personajes mediante un carrusel, tarjetas agrupadas y tarjetas en flexbox, cada una con información expandible.

## 📋 Descripción

Este proyecto es una página informativa de una sola vista (`index.html`) que muestra a nueve personajes del universo Marvel organizados en tres secciones:

1. **Carrusel principal** — Capitán América, Thor y Hulk, con imagen, descripción breve y un panel colapsable con información adicional.
2. **Grupo de tarjetas (card-group)** — Iron Man, Viuda Negra y Ojo de Halcón, en formato de tarjetas horizontales con botón "Más información".
3. **Tarjetas flexibles (flex-cards)** — Star-Lord y Hombre Araña, en tarjetas de ancho fijo distribuidas con `flexbox`.

Cada personaje cuenta con un color distintivo definido mediante variables CSS, y toda la información ampliada se muestra u oculta usando el componente `collapse` de Bootstrap.

## 🛠️ Tecnologías utilizadas

- **HTML5** — estructura semántica del contenido
- **CSS3** — estilos personalizados (`style.css`), variables CSS (custom properties) y flexbox
- **Bootstrap 5.3.8** — sistema de grid, carrusel, tarjetas (cards) y componentes colapsables, cargado vía CDN

## 📁 Estructura del proyecto

```
├── index.html      # Página principal con la monografía
├── style.css       # Estilos personalizados y colores por personaje
└── assets/         # Carpeta con las imágenes de los personajes 
```



## 🎨 Personajes incluidos

| Personaje | Sección | Rol/Descripción corta |
|---|---|---|
| Capitán América | Carrusel | Súper soldado, líder y símbolo de justicia |
| Thor | Carrusel | Dios del trueno, príncipe de Asgard |
| Hulk | Carrusel | Científico transformado en bestia de fuerza descomunal |
| Iron Man | Card group | Ingeniero genio, creador del traje de armadura |
| Viuda Negra | Card group | Espía y agente de combate cuerpo a cuerpo |
| Ojo de Halcón | Card group | Arquero de precisión sin poderes sobrehumanos |
| Star-Lord | Flex cards | Líder de los Guardianes de la Galaxia |
| Hombre Araña | Flex cards | Estudiante con poderes arácnidos, héroe de Nueva York |

## Cómo usarlo

1. Clona o descarga este repositorio.
2. Abre `index.html` directamente en tu navegador (no requiere servidor ni instalación de dependencias, ya que Bootstrap se carga desde CDN).

## Características

- Navbar fija (`sticky`) en la parte superior con buscador.
- Carrusel de imágenes con indicadores, controles previo/siguiente y descripciones colapsables.
- Colores de fondo únicos por personaje mediante variables CSS (`--bk-color-*`).
- Diseño responsivo gracias al sistema de grid de Bootstrap.
- Secciones adicionales de información ocultas por defecto, visibles al presionar "Más información".

## Autor

Proyecto realizado por **Jairo Cortés** como parte de una práctica de maquetación web con HTML, CSS y Bootstrap.
