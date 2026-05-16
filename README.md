<<<<<<< HEAD
# \# EndlessRunner Case Study

# 

# A prototype game with a simple "Endless Runner" mechanic. The character constantly runs forward, the player jumps/avoids obstacles and collects points, built in Unreal Engine 5.7.

# The primary focus of this project is on clean software architecture, fluid playability, and core game design principles.

# 

# \### Core Mechanics

# \- Continuous Movement: The character automatically sprints forward at a velocity that increases with time. 

# \- Responsive Controls: Features fluid jump mechanics mapped to Spacebar and Left Click. 

# 

# \### Procedural Track Generation

# \- Dynamic Tiling: The level continuously instantiates a series of modular track pieces ahead of the player.

# \- Memory Management: To maintain a performance, trailing tiles are systematically desawned and purged from memory after they leave the player's view.

# 

# \### Collectibles

# \- Coins

# \- Powerups: Different powerups make gameplay easier.

# 

# \### Hazard \& Scoring Systems

# \- Obstacle Spawner: A decoupled, randomized spawning algorithm that introduces two distinct types of hazards:

# &#x20; - Static Hazards: Stationary structural blockades.

# &#x20; - Dynamic Hazards: Moving obstacles requiring precise timing to bypass.

# \- Game Over Loop: Colliding with a hazard immediately triggers a game over state, caching player progress.

# \- Data Persistence: Tracks real-time distance metrics during the run and utilizes a SaveGame system to persist the highest score across sessions.

# 

# \### Controls

# &#x20; -  Jump / Double Jump: Spacebar / Left Click

# &#x20; - Switch Lanes: A - D / Left - Right Arrow Keys

# &#x20; -  Pause : ESC / P

# 

=======
# EndlessRunner Case Study

A prototype game with a simple "Endless Runner" mechanic. The character constantly runs forward, the player jumps/avoids obstacles and collects points, built in Unreal Engine 5.7.
The primary focus of this project is on clean software architecture, fluid playability, and core game design principles.

### Core Mechanics
- Continuous Movement: The character automatically sprints forward at a velocity that increases with time. 
- Responsive Controls: Features fluid jump mechanics mapped to Spacebar and Left Click. 

### Procedural Track Generation
- Dynamic Tiling: The level continuously instantiates a series of modular track pieces ahead of the player.
- Memory Management: To maintain a performance, trailing tiles are systematically desawned and purged from memory after they leave the player's view.

### Collectibles
- Coins
- Powerups: Different powerups make gameplay easier.

### Hazard & Scoring Systems
- Obstacle Spawner: A decoupled, randomized spawning algorithm that introduces two distinct types of hazards:
  - Static Hazards: Stationary structural blockades.
  - Dynamic Hazards: Moving obstacles requiring precise timing to bypass.
- Game Over Loop: Colliding with a hazard immediately triggers a game over state, caching player progress.
- Data Persistence: Tracks real-time distance metrics during the run and utilizes a SaveGame system to persist the highest score across sessions.

### Controls
  -  Jump / Double Jump: Spacebar / Left Click
  - Switch Lanes: A - D / Left - Right Arrow Keys
  -  Pause : ESC / P
>>>>>>> origin/main
