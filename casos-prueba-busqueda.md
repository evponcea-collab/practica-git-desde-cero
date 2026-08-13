# Casos de prueba: búsqueda

## CP-001 — Búsqueda con término válido

**Pasos:**

1. Abrir la página de búsqueda.
2. Escribir `audífonos`.
3. Ejecutar la búsqueda.

**Resultado esperado:** se muestran resultados relacionados con el término ingresado.


## CP-002 — Búsqueda sin resultados

**Pasos:**

1. Abrir la página de búsqueda.
2. Escribir `zxqv-no-existe`.
3. Ejecutar la búsqueda.

**Resultado esperado:** se informa que no hay resultados para el término ingresado.


CP-003 — Búsqueda con campo vacío

**Pasos:**

1. Abrir la página de búsqueda.
2. Dejar vacío el campo de búsqueda.
3. Ejecutar la búsqueda.

**Resultado esperado:** el sistema solicita ingresar un término de búsqueda.

## CP-004 - Búsqueda con caracteres especiales

**Pasos:**

1. Abrir la página de búsqueda.
2. Escribir ´@#$%´.
3. Ejecutar la búsqueda.

**Resultado esperado:** el sistema procesa la búsqueda de forma controlada y no presenta un error técnico.
