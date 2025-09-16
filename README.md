# InfiniteTunnel (Unreal Engine 5.6)

**InfiniteTunnel** is a fast-paced endless tunnel game built with Unreal Engine 4. The player must survive by avoiding obstacles, defeating enemies, and managing health while the game speed increases over time.  

This project began as a simple tunnel game tutorial and has been expanded with new gameplay mechanics, visuals, and challenges.  

---

## Features

- **Health System**  
  - On-screen health bar that decreases when colliding with walls or enemies.  
  - Health packs (bananas) restore lost health.  

- **Scoring**  
  - Score increases when successfully passing through obstacles.  

- **Enemies**  
  - Red blocks spawn randomly as enemies.  
  - Inflict the same damage as walls on contact.  
  - Can be destroyed with player projectiles.  

- **Projectile Attacks**  
  - Left mouse click fires projectiles.  
  - Projectiles destroy walls and enemies (except Evil Walls).  

- **Evil Walls**  
  - Special indestructible walls that instantly kill the player on impact.  
  - Textured similarly to tunnel walls to hint at their danger.  

- **Game Progression**  
  - Player speed gradually increases the longer they survive.  

- **Visual Enhancements**  
  - Enemies, health packs, and Evil Walls have unique textures to make them recognizable within the tunnel environment.  

---

## Gameplay

### Controls
- `Mouse Left Click` → Fire projectile  
- `Mouse` → Move  
- `Esc` → Quit  

### Objective
- Survive as long as possible.  
- Avoid or destroy obstacles and enemies.  
- Collect health packs to stay alive.  
- Earn a higher score by successfully navigating the tunnel.  

---

## Project Structure

- **Blueprints**  
  - Game logic for spawning, player health, scoring, and speed progression.  
- **Assets**  
  - Unique materials and textures for health packs, enemies, and Evil Walls.  
- **UI**  
  - HUD with score display and health bar.  

---

## Getting Started

1. Clone or download this repository.  
2. Open the `.uproject` file in Unreal Engine.  
3. Click **Play** to start the game.  

---

## Future Improvement Ideas

- Add sound effects and background music.  
- Expand projectile mechanics with different weapon types.  
- Introduce power-ups beyond health packs (e.g., shields, slow-motion).  

---
