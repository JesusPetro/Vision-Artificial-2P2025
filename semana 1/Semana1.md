# Semana 1

_04-08-2025 → 08-08-2025_

Durante esta primera semana del curso se realizó una introducción general a la materia de Visión Artificial, abarcando conceptos fundamentales y operaciones matriciales básicas que serán esenciales para el desarrollo del curso. Como actividad práctica, se asignó un laboratorio que permitirá aplicar los conocimientos teóricos adquiridos.

---

Inspirado en los estilos de mi vault de Obsidian, he decidido implementar dos _callouts_ personalizados para mejorar la estética y organización de las notas (por ejemplo, para resaltar una nota importante con "> Nota"). Los callouts definidos son de tipo `información` e `importante` (Info y Warning). A continuación se muestra la estructura recomendada para cada uno:

> **Nota**: Si se va a visualizar en GitHub, se recomienda ajustar los colores y separar el título en una etiqueta diferente para garantizar una correcta visualización.

### ⚠️ Warning

```html
<div
  style="border-left: 4px solid #f5c354; padding: 0.5em; background-color: rgba(243, 171, 44, 0.1); border-radius: 6px;"
>
  <strong style="color: #f3ab2c;">
    <svg
      xmlns="http://www.w3.org/2000/svg"
      width="15"
      height="15"
      viewBox="0 0 24 24"
      fill="none"
      stroke="currentColor"
      stroke-width="2"
      stroke-linecap="round"
      stroke-linejoin="round"
      style="vertical-align: -1px;"
    >
      <path
        d="m21.73 18-8-14a2 2 0 0 0-3.48 0l-8 14A2 2 0 0 0 4 21h16a2 2 0 0 0 1.73-3"
      />
      <path d="M12 9v4" />
      <path d="M12 17h.01" />
    </svg>
    Warning </strong
  ><br />
  <span style="color: #fff;"> [Texto de advertencia aquí] </span>
</div>
```

### ℹ️ Info

```html
<div
  style="border-left: 4px solid rgb(23, 146, 153); background-color: rgba(23, 146, 153, 0.1); padding: 0.5em; border-radius: 6px;"
>
  <strong style="color: rgb(23, 146, 153);">
    <svg
      xmlns="http://www.w3.org/2000/svg"
      width="15"
      height="15"
      viewBox="0 0 24 24"
      fill="none"
      stroke="currentColor"
      stroke-width="2"
      stroke-linecap="round"
      stroke-linejoin="round"
      style="vertical-align: -1px; margin-right: 4px;"
    >
      <circle cx="12" cy="12" r="10" />
      <path d="M12 16v-4" />
      <path d="M12 8h.01" /></svg
    >Info </strong
  ><br />
  <span style="color: #fff;">[Texto informativo aquí]</span>
</div>
```
