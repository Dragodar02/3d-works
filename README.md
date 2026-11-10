# 3D Works

<p align="center">
  <img src="renders/sneaker-beauty.jpg" alt="Sneaker — beauty render" width="800">
</p>

Studio renders and source files from my 3D work.  
Кросівок, змодельований і відрендерений у Blender.

## Sneaker

A stylized sneaker with a knit upper, translucent side panels, a strap-and-clip closure, and a textured air-cushion midsole. The scene is a modifier-heavy Blender setup (mirror, subdivision, solidify, shrinkwrap, bevel, and a hidden boolean cutter) and ships with its own camera and studio lights.

**Source file:** [`models/sneaker/sneaker.blend`](models/sneaker/sneaker.blend)

### Renders

| Beauty | Clay / wireframe |
| :---: | :---: |
| ![Beauty](renders/sneaker-beauty.jpg) | ![Clay and wireframe](renders/sneaker-clay-wire.jpg) |
| **Side** | **Front three-quarter** |
| ![Side angle](renders/sneaker-angle-left.jpg) | ![Front three-quarter](renders/sneaker-angle-right.jpg) |

### Scene stats

Counts were read from the `.blend` in Blender 4.5.16 LTS. They cover **render-visible** meshes with modifiers applied. The file was last saved in **Blender 3.3.6**.

| | |
| :--- | ---: |
| Vertices | 112,354 |
| Faces | 111,548 |
| Triangles | 223,888 |
| Visible mesh parts | 15 |
| Materials | 9 |
| Objects in the file | 25 (15 visible meshes, 1 hidden cutter, 5 lights, 1 camera, 3 empties) |
| Saved with | Blender 3.3.6 |

Base mesh before modifiers: **797** vertices, **269** faces, **527** triangles.

### Software

- Blender 3.3 or newer (scene created in 3.3.6)
- Cycles (the file’s render engine), CPU or GPU

### How to open

1. Install [Blender](https://www.blender.org/download/) 3.3 or later.
2. Open `models/sneaker/sneaker.blend`.
3. The camera and lights are already in the scene. Press **F12** (or *Render → Render Image*) to render.

### Portfolio

More work, including character, prop, and environment pieces: **[dragodar02.github.io/MySuperSite](https://dragodar02.github.io/MySuperSite/)**.

## Repository structure

```text
models/
  sneaker/
    sneaker.blend      # source scene
renders/
  sneaker-beauty.jpg
  sneaker-angle-left.jpg
  sneaker-angle-right.jpg
  sneaker-clay-wire.jpg
```

New pieces can follow the same layout: put the source file in `models/<work-name>/` and add preview renders under `renders/`.
