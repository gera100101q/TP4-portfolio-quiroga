# TP4 - Portfolio Personal — Gerardo Quiroga

Sitio web estático de portfolio personal con 4 páginas, enfocado en navegación, tipos de enlaces y estados CSS.

Desarrollado como Trabajo Práctico N°4 de **Laboratorio de Programación** — 6to año G, IPET 249 Nicolás Copérnico (2026).

## Páginas

- `index.html` — Inicio con hero y proyectos destacados
- `galeria.html` — Galería completa de proyectos
- `about.html` — Perfil, habilidades y trayectoria
- `contacto.html` — Formulario y datos de contacto con `mailto:`

## Estructura

```
TP4-portfolio-quiroga/
├── css/
│   └── estilos.css
├── img/
│   └── avatar.png
├── index.html
├── galeria.html
├── about.html
├── contacto.html
└── README.md
```

## Estados de links aplicados (CSS)

- `:link` → azul `#2563eb`
- `:visited` → violeta `#7c3aed`
- `:hover` → azul más oscuro + subrayado (feedback visual claro)
- `:active` → rojo `#dc2626` en el momento del clic

Los links del menú y los botones tienen sus propios estilos que sobreescriben los estados globales para mayor claridad visual.

## Principios de Steve Krug aplicados

1. **"Usted está aquí"**: clase `.activo` en el menú resalta la página actual con fondo azul.
2. **Convenciones**: logo arriba a la izquierda como enlace al inicio (imagen como link), menú en posición fija predecible.
3. **Eliminar el ruido**: sin textos de bienvenida innecesarios, cada sección tiene un único propósito claro.

## Ver en vivo

https://[tu-usuario].github.io/TP4-portfolio-quiroga/

## Autor

Gerardo Quiroga — gerardobenjaminquiroga2009@gmail.com
