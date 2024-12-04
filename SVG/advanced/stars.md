#### 1. Lluvia de estrellas

##### Instrucciones:

- **Objetivo:** Crear un fondo nocturno y generar estrellas de forma aleatoria con JavaScript.
- **Pasos:**
  1. Diseñar un fondo en SVG que simule el cielo nocturno (puedes usar un rectángulo con un gradiente oscuro).
  2. Crear un círculo pequeño para representar una estrella.
  3. Al cargar la página, generar al menos 10 estrellas en posiciones y tamaños aleatorios.
  4. Cada estrella debe tener un color ligeramente diferente (puedes usar variaciones de amarillo o blanco).
  5. **Interacción:** Al hacer clic en cualquier parte del fondo, debe generarse una nueva estrella en una posición aleatoria.
  6. Opcional: Las estrellas desaparecen después de 5 segundos con una animación de desvanecimiento.

##### Parámetros a tener en cuenta:

- Las posiciones deben ser totalmente aleatorias dentro del área del SVG.
- Los tamaños de las estrellas deben variar entre 2 y 10 píxeles de diámetro.
- Las nuevas estrellas deben añadirse al DOM SVG dinámicamente con `createElementNS`.

---

## Plantillas

```html
<svg
  id="sky"
  width="500"
  height="500"
  style="background: linear-gradient(to bottom, #001D3D, #003566);"></svg>
<script>
  // Tu código aquí
</script>
```
