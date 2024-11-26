# taller-tailwind

## Explicación:

## Ejercicio 1

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


## Ejercicio 2

## Explicación del diseño:

### Contenedor principal:
- **`min-h-screen`**: Asegura que el formulario ocupe toda la altura de la pantalla.
- **`flex items-center justify-center`**: Centra el formulario horizontal y verticalmente.
- **`bg-green-100`**: Fondo de color verde claro.

### Tarjeta del formulario:
- **`bg-white`**: Fondo blanco.
- **`p-6 rounded-lg shadow-lg`**: Añade padding, bordes redondeados y sombra.

### Botón de Google:
- **`flex items-center justify-center`**: Permite alinear el icono y el texto.
- **`bg-green-200 hover:bg-green-300`**: Fondo verde claro con un efecto hover.

### Inputs del formulario:
- **`block w-full px-3 py-2 border`**: Estilo básico para los campos de texto.
- **`focus:outline-none focus:ring-green-500`**: Resalta el campo activo con un borde verde.

### Diseño responsivo:
- **`w-full max-w-md`**: Asegura que el formulario sea responsivo, con un ancho máximo en pantallas grandes.

### Resultado esperado en dispositivos:
- **XS/SM**: El formulario ocupa casi todo el ancho de la pantalla.
- **LG**: El formulario se centra con suficiente espacio a los lados.
- **FULL**: Similar a **LG**, pero con más espacio en el contenedor.
