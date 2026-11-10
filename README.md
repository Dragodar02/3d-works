# 3D Works

<p align="center">
  <img src="renders/sneaker-beauty.jpg" alt="Sneaker — beauty render" width="800">
</p>

Studio renders, turntables, and source files from my 3D work.

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

## Gallery

### HUTSUL 3.2 lens

A close-up of a camera lens with a petal hood, marked **HUTSUL 3.2** and **Kosiv.ZS**, under purple rim light.

<p align="center">
  <img src="renders/lens-hutsul.jpg" alt="HUTSUL 3.2 lens — Kosiv.ZS" width="800">
</p>

### Mushroom character

A stylized mushroom character on a rock, with a red-and-yellow cap and a soft forest bokeh behind it.

<p align="center">
  <img src="renders/mushroom-character.jpg" alt="Mushroom character on a rock" width="800">
</p>

### Mouse character

A fluffy mouse with huge ears and round glasses, in a red hoodie, holding a cup.

<p align="center">
  <img src="renders/mouse-character.jpg" alt="Mouse character in glasses and a red hoodie" width="800">
</p>

### Nike fabric

A dark mesh fabric / seat study with a repeating Nike swoosh pattern.

<p align="center">
  <img src="renders/nike-fabric.jpg" alt="Dark Nike-swoosh fabric" width="800">
</p>

### Turntables

Click a preview to open the MP4.

<p align="center">
  <a href="videos/nike-headphones.mp4">
    <img src="renders/nike-headphones-preview.gif" alt="Nike headphones — turntable preview" width="400">
  </a>
  <a href="videos/lens-hutsul.mp4">
    <img src="renders/lens-hutsul-preview.gif" alt="HUTSUL 3.2 lens — camera-move preview" width="400">
  </a>
</p>
<p align="center">
  <a href="videos/nike-headphones.mp4">Nike headphones</a>
  ·
  <a href="videos/lens-hutsul.mp4">HUTSUL 3.2 lens</a>
</p>

## Portfolio

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
  lens-hutsul.jpg
  mushroom-character.jpg
  mouse-character.jpg
  nike-fabric.jpg
  nike-headphones-preview.gif
  lens-hutsul-preview.gif
videos/
  nike-headphones.mp4
  lens-hutsul.mp4
```

New pieces can follow the same layout: put the source file in `models/<work-name>/`, preview stills and GIF previews under `renders/`, and turntables under `videos/`.
