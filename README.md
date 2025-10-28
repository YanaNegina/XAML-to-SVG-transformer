# XAML-to-SVG-transformer
This repository contains 21 simple geometric figures converted from XAML to SVG (originally created for psychophysiolotgy experiment purposes).

All SVGs:
- use a **400×400** `viewBox` (the thin stroked cross is upscaled to 400×400 too, but it's optional),
- are **centered** within the canvas,
- have a **transparent background**,
- are **black** (`#000000`).

## Files

- `arrow.svg`
- `circle.svg`
- `crescent.svg`
- `cross_lines.svg` (thin stroked cross = fixation cross)
- `cross_solid.svg` (solid cross)
- `diamond.svg`
- `ellipse.svg`
- `equilateral_triangle.svg`
- `flag.svg`
- `flash.svg`
- `half_circle.svg`
- `heart.svg`
- `octahedron.svg`
- `parallelogram.svg`
- `pentahedron.svg`
- `rectangle.svg`
- `rightangled_triangle.svg`
- `ring.svg`
- `star_12_point.svg`
- `star_5_point.svg`
- `trapezium.svg`

## Notes
* XAML’s path syntax is compatible with SVG’s, after removing WPF-only prefixes.
* The drawing space is always 400×400 “units,” independent of display size.
* If you want to recolor, either change the `fill`/`stroke` value in the file.
