# ArcGIS Enterprise in Higher Education

Static pages for GitHub Pages. No build step.

| File | What it is |
|---|---|
| `index.html` | Landing page linking the three documents |
| `educator-hub.html` | Enterprise GIS Educator Hub (resource library with search and filters) |
| `curriculum-pattern.html` | Enterprise GIS Curriculum Pattern |
| `enterprise-explained.html` | ArcGIS Enterprise Explained (IT primer) |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Publish

1. Create a repository and upload every file in this folder to its root (including `.nojekyll`).
2. Settings > Pages > Build and deployment > Source: "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
3. After a minute the site is at `https://<account>.github.io/<repository>/`.

## Embed

Each page has its own address, for example
`https://<account>.github.io/<repository>/educator-hub.html`.

- ArcGIS Experience Builder: add an Embed widget, choose "Embed by URL", paste the address.
- ArcGIS Hub: add an iframe card to the site or page layout and paste the address.

Links to outside sites open in a new browser tab, so they work from inside an embedded frame.
Links between the three documents and in-page section links stay inside the frame.
