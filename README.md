# Nombre Agencia — Web

Web corporativa para presentar la agencia de agentes de IA: quiénes somos,
qué hacemos y cómo contactarnos.

## Estructura

```
index.html    → estructura y contenido de todas las secciones
styles.css    → estilos base (layout, tipografía, colores, responsive)
script.js     → interactividad (menú, animaciones, formulario)
```

## Cómo verla en local

No hace falta servidor: abre `index.html` directamente en el navegador,
o usa la extensión "Live Server" de VS Code para recarga automática.

## Flujo de trabajo

- `main` contiene siempre una versión funcional de la web.
- Cada cambio se hace en una rama propia (`feature/nombre-del-cambio`).
- Antes de fusionar a `main`, se abre un Pull Request para revisión.

## Reparto de trabajo

- **Estructura y contenido**: HTML semántico + CSS base.
- **Interactividad y estilos**: animaciones, transiciones, hover, validación
  de formulario, menú móvil.
