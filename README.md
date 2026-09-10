# ByteDash — CS-5105N Game Development

**Author:** Charles Adrian D. Mercader
**Course:** CS-5105N Game Development
**Engine:** Godot 4.x

## Game Concept

A little pixel character auto-running through a glitchy digital corridor, dodging obstacles that spawn faster over time. Fits a CS course thematically without needing custom art skills early on.

## Weekly Activity Log

### Week 1 — Godot \& Git Setup

**Objective:** Set up the development environment, initialize version control, and get a running "Hello World" 2D scene.

**What I did:**

* Installed Godot 4.x (Standard build) and created a new project.
* Built a minimal scene: `Node2D` root → `Sprite2D` child with a placeholder texture.
* Confirmed the scene runs (F5) without errors.
* Initialized Git (`git init`), added a Godot-specific `.gitignore`.
* Set up Git LFS to track large binary art assets (`\*.png`, `\*.wav`).
* Made the initial commit and pushed to a private GitHub repo (made public for submission).

**Scene structure:**

```
Node2D (root)
└── Sprite2D
```

**Evidence:**

!\[Hello World scene running in Godot](screenshots/week1-hello-world.png)
*Caption: Godot editor showing the running scene with the placeholder sprite.*

**Commands used:**

```bash
git init
git lfs install
git lfs track "\*.png" "\*.wav"
git add .
git commit -m "Week 1: project setup + Hello World"
git push -u origin main
```

**Notes / issues encountered:** None so far

\---

### Week 2 — \[Title]

*(To be added)*

### Week 3 — \[Title]

*(To be added)*

### Week 4 — \[Title]

*(To be added)*

### Week 5 — \[Title]

*(To be added)*

### Week 6 — \[Title]

*(To be added)*

### Week 7 — \[Title]

*(To be added)*

### Week 8 — \[Title]

*(To be added)*

## Repository Structure

```
.
├── project.godot
├── scenes/
├── scripts/
├── assets/
├── screenshots/
└── README.md
```

