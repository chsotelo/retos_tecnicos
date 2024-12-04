#### 2. Gráfico de barras dinámico

##### Instrucciones:

- **Objetivo:** Dibujar un gráfico de barras SVG y permitir que los valores cambien dinámicamente con el mouse.
- **Pasos:**
  1. Dibujar un eje X y un eje Y (líneas horizontales y verticales).
  2. Crear al menos 5 barras con diferentes alturas iniciales.
  3. Añadir etiquetas de texto debajo de cada barra para identificarlas (por ejemplo, A, B, C, etc.).
  4. **Interacción:** Al mover el mouse sobre una barra, su altura debe cambiar (por ejemplo, aumentar o disminuir entre un rango de 50 a 200 píxeles).
  5. Al salir el mouse de la barra, esta vuelve gradualmente a su altura original.
  6. Opcional: Añadir un botón para generar un conjunto completamente nuevo de valores aleatorios para las barras.

##### Parámetros a tener en cuenta:

- Las barras deben ser rectángulos (`<rect>`) dentro del SVG.
- La altura inicial debe estar entre 50 y 150 píxeles.
- Las etiquetas deben alinearse correctamente con cada barra.
- El cambio de altura al pasar el mouse debe tener una animación suave usando `requestAnimationFrame` o transiciones.

## Plantilla

```html
<svg id="chart" width="500" height="300" style="background: #f4f4f4;">
  <!-- Ejes -->
  <line x1="50" y1="250" x2="450" y2="250" stroke="black" />
  <line x1="50" y1="250" x2="50" y2="50" stroke="black" />
</svg>
<script>
  // Tu código aquí
</script>
```
