# 🏰 Tower Defense Game (Algorithm Analysis Project)

A browser-based **Tower Defense Game** built with **HTML5 Canvas, CSS, and JavaScript**, created as part of a **Design & Analysis of Algorithms (DAA) project**.  
The game demonstrates key algorithmic concepts through interactive gameplay and a dedicated algorithm analysis section.

---

## 🎮 Features
- Enemy movement along a fixed path
- Tower placement, upgrades, and targeting
- Multiple enemy types with sprite animations
- Gold, wave, lives, and score tracking
- Drag-and-drop tower placement from palette
- Interactive algorithm analysis section with **visual demonstrations**

---

## 🧮 Algorithms Implemented

This project highlights **five important algorithms** used in Tower Defense game design:

1. **Pathfinding (Enemy Movement)**  
   - Enemies follow a fixed path from spawn to goal.  
   - Mimics **Breadth-First Search (BFS)** or simple path array traversal.

2. **Collision Detection (Tower Range Check)**  
   - Towers check which enemies are in range using the **Euclidean distance formula**.  
   - Ensures only nearby enemies are attacked.

3. **Target Selection (Greedy Choice)**  
   - Towers pick targets based on modes: **First**, **Strongest**, or **Weakest**.  
   - Demonstrates greedy selection strategy.

4. **Wave Spawning (Queue Scheduling)**  
   - Enemies are spawned sequentially using a **queue (FIFO)**.  
   - Each wave dequeues enemies one by one.

5. **Tower Placement Validation**  
   - Algorithm checks if a tile is valid for tower placement.  
   - Prevents overlapping towers or blocking the enemy path.

---

## 📂 Project Structure

