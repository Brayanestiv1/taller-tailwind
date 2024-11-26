# taller-tailwind

## Explicación:

### Grid layout responsivo:
- **`grid`**: Activa el sistema de grillas.
- **`gap-4`**: Espacio entre las tarjetas.
- **`sm:grid-cols-2`**, **`lg:grid-cols-3`**, **`xl:grid-cols-4`**: Define el número de columnas según el tamaño de la pantalla.
  - **`sm`**: Pantallas pequeñas.
  - **`lg`**: Pantallas grandes.
  - **`xl`**: Pantallas extra grandes.

### Diseño responsivo:
- Usamos clases como **`sm:grid-cols-2`** para manejar cómo las tarjetas se distribuyen en pantallas pequeñas (2 columnas en este caso).
- En pantallas grandes, la clase **`lg:grid-cols-3`** muestra 3 columnas, y **`xl:grid-cols-4`** muestra 4.

### Estilo de tarjetas:
- **`border-2`**: Borde de 2px.
- **`rounded-lg`**: Esquinas redondeadas.
- **`p-4`**: Padding interno.
- **`text-lg`**, **`text-sm`**, **`font-semibold`**: Tamaño y peso del texto.

### Resultado esperado:
- **XS (pantallas pequeñas)**: Una columna.
- **SM (pantallas medianas)**: Dos columnas.
- **LG (pantallas grandes)**: Tres columnas.
- **XL y FULL**: Cuatro columnas.
