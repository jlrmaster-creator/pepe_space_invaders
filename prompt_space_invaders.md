**Contexto y Rol**
Actúa como un desarrollador experto en videojuegos arcade 2D para navegador, con especial enfoque en rendimiento, diseño visual atractivo y optimización para dispositivos móviles. Debes crear un juego con estética clásica tipo *Space Invaders*, pero con un acabado moderno y pulido.

**Consulta / Tarea**
Desarrollar una aplicación web tipo arcade donde el jugador controla una nave en la parte inferior de la pantalla que dispara proyectiles hacia enemigos que aparecen desde la parte superior. El objetivo es sobrevivir el mayor tiempo posible y conseguir la máxima puntuación.

**Especificaciones**

**Mecánica principal:**

* El jugador controla una nave situada en la parte inferior:

  * Puede moverse horizontalmente (izquierda/derecha).
  * Dispara proyectiles hacia arriba.
* Enemigos (naves):

  * Aparecen desde la parte superior de la pantalla.
  * Se generan de forma aleatoria:

    * Individuales
    * En parejas
    * En tríos
    * En grupos más grandes
* Movimiento descendente progresivo de los enemigos.

**Sistema de combate:**

* Cada nave enemiga tiene resistencia variable:

  * Algunas se destruyen con 1 disparo
  * Otras requieren múltiples impactos
* Colisiones:

  * Disparo impacta → daño o destrucción
  * Enemigo impacta con el jugador → fin del juego

**Sistema de puntuación:**

* Contador de puntos visible:

  * Aumenta por cada nave destruida
  * Puntos variables según dificultad del enemigo (opcional)

**Dificultad progresiva:**

* Aumento gradual de:

  * Frecuencia de aparición de enemigos
  * Velocidad de descenso
  * Resistencia de enemigos
* Escalado progresivo, no abrupto

**Controles:**

* Adaptado a móvil (prioridad mobile-first):

  * Botón táctil izquierda
  * Botón táctil derecha
  * Botón táctil disparo
  * Botón de pausa
* Soporte adicional para teclado:

  * Flechas izquierda/derecha
  * Barra espaciadora para disparar

**Interfaz (UI):**

* Pantalla inicial:

  * Título del juego
  * Botón “Jugar”
* Pantalla de juego:

  * HUD con:

    * Puntuación
    * Botón de pausa
* Pantalla final:

  * Mostrar puntuación final
  * Botón de reinicio

**Diseño visual:**

* Estilo arcade clásico con toque moderno
* Fondo espacial animado (estrellas, galaxias, etc.)
* Colores vivos y contrastados
* Animaciones:

  * Disparos
  * Explosiones
  * Movimiento de enemigos

**Audio:**

* Sonido de disparo
* Sonido de explosión
* Sonido ambiente espacial (loop suave)
* Opcional: música arcade retro

**Tecnología sugerida:**

* HTML5, CSS3, JavaScript
* Canvas API o Phaser.js
* Diseño responsive adaptado a móviles

**Criterios de Calidad**

* Rendimiento fluido (mínimo 60 FPS)
* Controles precisos en móvil
* Código limpio, modular y escalable
* Buena experiencia visual y sonora
* Jugabilidad adictiva y equilibrada

**Cómo debe ser la respuesta**

* Incluir:

  * Estructura del proyecto
  * Código funcional base
  * Explicación clara de la lógica principal
* Priorizar claridad, rendimiento y jugabilidad
* Mantener equilibrio entre simplicidad y acabado profesional
