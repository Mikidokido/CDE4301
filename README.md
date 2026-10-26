# CDE4301 RoboMaster capstone website starter

This two-page *original* design takes general organisational inspiration from the VATEL CDE4301 example (a concise project showcase with a separate full interim report). It does **not** reuse VATEL's HTML, CSS, JavaScript, illustrations or source files.

## Site structure

```
index.html              # Project overview / homepage
styles.css              # Homepage styling
interim-report/
  index.html            # Detailed CDE4301 report (original report starter)
assets/
  README.md             # Where your approved figures and photos will go
```

## Publish with GitHub Pages

1. Extract this ZIP. Do not upload the ZIP file itself.
2. Edit `index.html` and `interim-report/index.html` in VS Code.
3. In GitHub create a repository (for example `cde4301-robomaster`).
4. Upload the contents of this extracted folder to the **root** of the repository, or use VS Code **Source Control > Initialize Repository > Commit > Publish to GitHub**.
5. Go to repository **Settings > Pages**. Source: **Deploy from a branch**. Branch: `main`, folder: `/(root)`. Click **Save**.
6. Your homepage will be at `https://YOURUSERNAME.github.io/cde4301-robomaster/` and the report at `/interim-report/` after deployment.

## Required customisation

- Replace all bracketed text and generic descriptions with your actual project scope, work and results.
- In the homepage `#targets` section, enter justified quantitative targets and test methods; current categories are only examples.
- Remove unused subsystem cards; include only real project workstreams.
- Add approved figures to `assets/`, link relative paths such as `assets/chassis-cad.png` on the homepage and `../assets/chassis-cad.png` in the interim report.
- For group projects, clearly distinguish individual contribution in the full report.
- Confirm report word limit and deadline against your assessment brief.
- Do not publish proprietary or confidential team CAD/materials without permission.

## Why two pages?

- The **homepage** provides a quick story and overview that an examiner can scan rapidly.
- The **interim report** houses detailed calculations, evidence, method, testing and citations, aligned to CDE4301 A1–A6.
- GitHub Pages works with HTML and CSS as uploaded, without building or installing dependencies.

## Notes

This is a working structural template, not a claim that any particular mechanical solution has been built or tested. All placeholders are intentional.
