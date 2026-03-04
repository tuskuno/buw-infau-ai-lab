# Project B: Street Network Analysis Map

## What You'll Build

An interactive map that visualizes and analyzes a street network with color-coded segments.

## Setup

Copy `street-network.geojson` into your project folder (sample provided in `workshop/data/`).

---

## Starter Prompt

```
Create a web page with a Leaflet map that loads street-network.geojson.
Color each street segment by its length property (short=green, long=red).
Add a legend. Make it fullscreen. Use a dark basemap.
```

---

## Advanced: React + shadcn Version

If you set up a Vite + React project (see Part 2b in the README), try this starter instead:

```
Create a React page using shadcn components with a Leaflet map that loads
street-network.geojson. Color each street segment by its length property
(short=green, long=red). Add a legend using a shadcn Card. Make it
fullscreen. Use a dark theme.
```

---

## Next Steps

Try these one at a time, after each previous step is working:

### Step 2: Click to Inspect

```
Add a click handler that highlights the selected street and shows its properties
```

### Step 3: Network Statistics

```
Calculate and display basic network statistics: total length, number of segments, average segment length
```

### Step 4: Heatmap

```
Add a heatmap layer toggle showing street density
```

---

## Bonus Ideas

- *"Add a filter to show only streets longer than a threshold (add a slider)"*
- *"Color streets by type instead of length, with a toggle to switch between them"*
- *"Add a drawing tool that lets me measure distances on the map"*
