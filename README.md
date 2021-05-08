# academic-illustration-assets

Assets for creating illustrative figures (and video figures) released under CC0 (public domain)

## Background

I have published several papers in the computer graphics and human-computer interaction domains. For creating the figures, video figures, and presentation slides of those papers, I repeatedly reused several common assets (such as `pointer.ai` for illustrating GUI interactions). However, every time I tried to do this, I needed to salvage those assets from old projects.

## Goal

The goal of this repository is to improve the reusability of my assets for accelerating future projects.

## Design Principles

### Colors

- Black: `#231F20`, `#4C4C4D`
- Accent: `#CE6B68`, `#C1272D`

### Illustrators (`*.ai`)

- Color mode: RGB
- Units: Pixels
- PDF compatible file

### After Effects (`*.aep`)

- 29.97 fps (`pointer.aep`)
- 30.00 fps (the others including future assets)

### Fonts

- Linux Libertine (`brew cask install font-linux-libertine`)
- Linux Biolinum (`brew cask install font-linux-biolinum`)

Math equations are rendered through LaTeX with the following options:
```latex
\usepackage{libertine}
\usepackage[libertine]{newtxmath}
```

### Font Sizes

- 96pt

## Assets

| file name       | preview                         |
| :-------------- | :------------------------------ |
| pointer         | ![](./docs/pointer.jpg)         |
| pointer-zoom    | ![](./docs/pointer-zoom.jpg)    |
| 1-slider-window | ![](./docs/1-slider-window.jpg) |
| slider-00       | ![](./docs/slider-00.png)       |
| ...             | ...                             |
| slider-05       | ![](./docs/slider-05.png)       |
| ...             | ...                             |
| slider-10       | ![](./docs/slider-10.png)       |
| dnn-1           | ![](./docs/dnn-1.jpg)           |
| dnn-2           | ![](./docs/dnn-2.jpg)           |
| function-1      | ![](./docs/function-1.jpg)      |
| function-2      | ![](./docs/function-2.jpg)      |
| speaker-0       | ![](./docs/speaker-0.jpg)       |
| speaker-1       | ![](./docs/speaker-1.jpg)       |
| speaker-2       | ![](./docs/speaker-2.jpg)       |
| speaker-3       | ![](./docs/speaker-3.jpg)       |
| loading         | ![](./docs/loading.jpg)         |
