# pacman
Some key points to check:
1. KeyEvent Handling**: Ensure `pacman.updateDirection(...)` is properly called for all arrow keys.
2. Ghost Movement**: If ghosts are not moving as expected, check the `updateDirection` method and ensure they don't get stuck.
3. Collision Detection**: If Pac-Man or ghosts clip through walls, tweak the collision logic.
4. Game Over Handling**: Ensure resetting works properly after losing all lives.
