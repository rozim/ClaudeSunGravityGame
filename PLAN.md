# Plan: Sun Gravity Game

## Overview
A 600x400 HTML5 Canvas game where the player shoots projectiles from a gun (triangle) on the right side,
aiming at targets (squares) on the left side. A sun in the center exerts gravity, curving the shot path.

## Steps

- [x] 1. Create `index.html` with canvas setup (600x400), basic structure, and CSS
- [x] 2. Implement the Sun - large circle in center, drawn with glow effect, applies gravity to projectiles
- [x] 3. Implement the Gun - triangle on right side, player moves it up/down (arrow keys) and rotates it (left/right arrows)
- [x] 4. Implement Targets - 6 small squares arranged on left side
- [x] 5. Implement Projectile physics - simulate gravity pull from sun each frame, detect collisions with targets and sun
- [x] 6. Implement shooting - spacebar fires a projectile from gun tip in aimed direction
- [x] 7. Implement scoring - +1 per target hit, display score, respawn targets when all cleared
- [x] 8. Add shot trajectory preview (dashed arc showing predicted path)
- [x] 9. Polish - colors, labels, particle effects, space background with stars
