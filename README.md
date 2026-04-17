# MiniWorldBox

Sandbox de simulación inspirado en WorldBox, construido con **Godot 4**.

## Objetivo
Crear un simulador 2D donde el jugador pueda:

- generar terreno
- spawnear humanos
- alterar el clima y el ambiente
- observar crecimiento, conflicto y colapso de civilizaciones

## Estado actual
Repositorio inicializado con una estructura base para empezar el prototipo.

## Stack
- **Engine:** Godot 4
- **Lenguaje:** GDScript
- **Arquitectura inicial:** escena principal + simulación por ticks + mundo en grilla

## Roadmap resumido

### Fase 1
- mapa por tiles
- generación procedural básica
- aldeanos simples
- recursos: comida y madera
- herramientas del jugador: fuego, agua, humanos

### Fase 2
- facciones
- combate
- animales
- incendios y propagación
- clima

### Fase 3
- reinos
- caminos
- barcos
- historia del mundo
- guardado de partidas

## Estructura

```text
.
├── docs/
│   └── ROADMAP.md
├── scenes/
│   └── Main.tscn
├── scripts/
│   └── Main.gd
├── .gitignore
└── project.godot
```

## Cómo abrir
1. Abrir Godot 4.
2. Importar este repositorio.
3. Ejecutar la escena principal.

## Próximo paso recomendado
Implementar el `WorldGrid` con tiles de agua, tierra, bosque y montaña.
