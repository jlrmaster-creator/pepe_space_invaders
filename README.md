# ⚡ Pepe Space Invaders

Un arcade espacial tipo *Space Invaders* con temática Pepe, desarrollado con HTML5 Canvas, CSS3 y JavaScript. Optimizado para **móvil** y navegador.

## 🎮 Cómo jugar

Abre [`1.html`](1.html) en tu navegador y pulsa **JUGAR**.

### Controles táctiles (móvil)
| Botón | Acción |
|-------|--------|
| ◀ ▶ | Moverse izquierda / derecha |
| 🔥 | Disparar |
| ⏸ | Pausar |
| Tocar la pantalla | Auto-disparo continuo |

### Controles teclado (PC)
| Tecla | Acción |
|-------|--------|
| ← → / A D | Moverse |
| Espacio | Disparar |
| P | Pausar |

## 🧬 Mecánicas

- **Enemigos** con resistencia variable (1-5 impactos)
- **Dificultad progresiva**: más enemigos, más rápidos y más resistentes con cada nivel
- **Jefes** grandes que aparecen aleatoriamente
- **Sistema de puntuación** con niveles (subir de nivel al alcanzar cierto score)
- **Efectos**: explosiones, estelas, estrellas con parallax, glow en naves
- **Sonido** procedural generado con Web Audio API (sin archivos externos)

## 🛠 Tecnología

- HTML5 + CSS3
- JavaScript (Canvas API)
- Web Audio API para sonido procedural
- Diseño responsive mobile-first

## 📁 Estructura

```
pepe_space_invaders/
├── 1.html          # Juego completo
└── README.md       # Este archivo
```

## 🚀 Despliegue

Abrir `1.html` en cualquier navegador moderno. No requiere servidor ni dependencias.
