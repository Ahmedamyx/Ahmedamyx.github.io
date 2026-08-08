# Ahmed Boubakry Portfolio

Personal portfolio site. Robotics and computer vision: computational imaging, medical image
analysis, control and mobile robotics.

Live at **[ahmedamyx.github.io](https://ahmedamyx.github.io)**

## Contents

```
index.html     the whole site (structure, styles and scripts inline)
assets/        images, animations, logos, the display font and the CV
.nojekyll      tells GitHub Pages to serve files as-is
```

## Notes

- Static, no build step and no dependencies. Open `index.html` locally or push to publish.
- Figures come from the reports in the individual project repositories.
- The 3-D comparison viewers are canvas renderers over meshes quantised into the page; the
  reconstruction meshes are sampled from the ground-truth and predicted `.ply` files.
- Respects `prefers-reduced-motion` and follows the visitor's light or dark theme, with a manual
  toggle in the header.
