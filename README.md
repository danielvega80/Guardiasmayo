# Guardias Taxi Mayo 2025 — Cangas de Onís

Esta microapp muestra de forma simple y rápida quién está de guardia cada día en mayo de 2025 en Cangas de Onís.  

Permite:
- Consultar el taxi de guardia por día específico.
- Consultar los turnos en un rango de fechas.
- Funciona perfectamente en móviles y escritorio.
- Código 100% libre para personalización.

---

## Cómo acceder

Una vez publicado en GitHub Pages, accede desde:

`https://TUUSUARIO.github.io/NOMBREDELREPO/`

(sustituye por tu usuario y nombre real del repositorio).

---

## Cómo actualizar los datos

Si necesitas cambiar las fechas o turnos:
1. Edita el archivo `index.html`.
2. Busca la sección de JavaScript con la variable:
   ```js
   const guardias = {
       1: 'Independientes P1',
       2: 'Independientes P1',
       // ...
   };
