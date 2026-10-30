# Ruleta Skibidi

Ruleta de cartas para el Teamlocke de Pokémon: gira la rueda y descubre qué carta te toca. Es una sola página (`index.html`) sin dependencias; basta con abrirla en el navegador o publicarla con GitHub Pages.

## Funciones

- Ruleta con las 86 cartas de la carpeta `cartas/`. Muestra la carta que pasa bajo el puntero y, al parar, resalta la ganadora.
- Modo **sin repetir**: las cartas que ya han salido se quitan de la ruleta hasta que las devuelvas.
- Botón para barajar el orden de la ruleta.
- Sonido opcional al girar; la preferencia se guarda en el navegador.
- Registro de las cartas que han salido en la sesión (se borra al recargar).
- Galería con todas las cartas y buscador.
- Atajos: `Espacio` para girar y `Esc` para cerrar la carta.

## Añadir una carta

1. Sube la imagen a `cartas/` (mejor en `.webp`, unos 900×1241 px).
2. Añade una línea a la lista `ALL_CARDS` de `index.html`:

   ```js
   { name: "Nombre de la carta", image: "cartas/archivo.webp" },
   ```
