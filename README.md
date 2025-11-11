# GameAI-FSM-Pathfinding-
# 🎮 Game AI – Reactive NPCs using FSM, A* & Greedy Pathfinding (Unity C#)

## 🧠 Project Overview

This project demonstrates **game AI architecture** in a top-down labyrinth environment, including:

- **Player** navigation using **A\* search**
- **4 Reactive NPCs** driven by **Finite State Machines**
- **State-based decision making** using in-game triggers and markers
- **Greedy Best-First Search** for patrol/roaming
- **A\*** for chase, attack, and escape behaviors
- **Waypoint graph traversal** for navigation

---

## 🤖 AI Components

| Component | Description |
|---|---|
| NPC Architecture | Moore-based Finite State Machine (DFA) |
| Number of Agents | 4 Unique reactive NPCs |
| States per NPC | Minimum 3 (Patrol, Chase, Hide, etc.) |
| Pathfinding | A* & Greedy Best-First |
| Navigation | Waypoint graph system |
| Triggers | Proximity and event-based state transitions |

---

## 🔄 Behaviour Logic

| NPC Behaviour | Pathfinding Used |
|---|---|
| Patrol / Roam | Greedy Best-First Search |
| Chase / Attack | A* Search |
| Hide / Escape | A* Search |
| Optional Behaviours | Either algorithm allowed |

### Example FSM Flow:

```
[Patrol] --(PlayerSeen)--> [Chase]
[Chase]  --(LowHealth)--> [Hide]
[Hide]   --(Safe)--------> [Patrol]
```

> Uses **Moore Machine logic** → actions depend purely on the active state.

---

## ✅ What I Learned

✔ Implemented FSM-driven decision making  
✔ Applied heuristic pathfinding algorithms in games  
✔ Built dynamic agent reactions using triggers  
✔ Designed scalable modular NPC architecture  
✔ Integrated AI theory into real-time simulation  

---

## 🧩 Key Concepts Used

- Moore-based Finite State Machines
- Heuristic Pathfinding (A*, Greedy Best-First)
- Trigger-based State Transitions
- Reactive Agent Behaviour
- Graph Navigation Systems

