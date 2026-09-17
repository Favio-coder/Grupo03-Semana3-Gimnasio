# Trabajo Grupal

## Integrantes

- Richard Favio Asturimac Medina 
- Brittany Gonzales Quiñones

## Conflictos de especificidad entre Bootstrap y Tailwind

Durante el desarrollo del Hero Section se utilizaron Bootstrap y Tailwind CSS de manera híbrida.

Bootstrap se utilizó principalmente para la estructura responsiva, el sistema de grid, la tipografía y las utilidades de layout como `container`, `row`, `col-*`, `display-3`, `lead`, `d-flex` y `gap-3`.

Tailwind CSS se utilizó para personalizar el diseño visual mediante colores, gradientes, sombras, espaciado, bordes, efectos hover y utilidades como `text-balance` y `max-w-3xl`.

Se presentaron algunos conflictos de especificidad debido a que Bootstrap también define estilos para componentes y utilidades. Para resolverlos se utilizaron clases de Tailwind con modificador `!` cuando fue necesario, permitiendo que dichas reglas tengan prioridad sobre los estilos de Bootstrap.

De esta manera, Bootstrap se mantiene responsable del comportamiento y estructura, mientras que Tailwind se utiliza principalmente para la personalización visual.