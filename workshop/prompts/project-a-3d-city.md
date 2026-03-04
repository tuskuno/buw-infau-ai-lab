# Project A: Interactive 3D City Viewer

## What You'll Build

A browser-based 3D viewer for an architectural city model with interactive features.

## Setup

Copy `city-model.glb` into your project folder (the instructor will provide this file).

---

## Starter Prompt

```
Create a web page that loads the 3D model from city-model.glb using Three.js.
Add orbit controls so I can rotate and zoom. Add a light gray ground plane.
Use a dark background. Make it fullscreen.
```

---

## Advanced: React + shadcn Version

If you set up a Vite + React project (see Part 2b in the README), try this starter instead:

```
Create a React page using shadcn components that loads the 3D model from
city-model.glb using Three.js with @react-three/fiber. Add orbit controls
so I can rotate and zoom. Add a light gray ground plane. Use a dark theme
with shadcn's dark mode. Make it fullscreen.
```

---

## Next Steps

Try these one at a time, after each previous step is working:

### Step 2: Click to Select

```
Add raycasting so when I click a building it highlights in orange and shows its name
```

### Step 3: Info Panel

```
Add a sidebar panel that shows building properties when selected
```

### Step 4: Minimap

```
Add a minimap in the corner showing a top-down view
```

---

## Bonus Ideas

- *"Add a search box that finds and zooms to a building by name"*
- *"Add a slider that controls sunlight direction and shows shadows"*
- *"Add a measurement tool that shows distance between two clicked points"*
