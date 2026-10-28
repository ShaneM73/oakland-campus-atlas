# Oakland Campus Atlas

**▶ Open the live web app: [shanem73.github.io/oakland-campus-atlas](https://shanem73.github.io/oakland-campus-atlas/)**

**Designer and main contributor:** Prof. Xin (Shane) Miao, Missouri State University ([@ShaneM73](https://github.com/ShaneM73))

An interactive 3D infographic of Oakland, Pittsburgh, comparing the University of Pittsburgh and Carnegie Mellon University.
Buildings, roads and parks come from OpenStreetMap.

Map data © OpenStreetMap contributors, available under the Open Database License (https://www.openstreetmap.org/copyright).

## Files
- `index.html` - the page
- `oakland-app.js` - page code with the 3D engine (three.js) bundled in
- `oakland.json` - buildings, roads and parks converted from an OpenStreetMap export

Keep all three files in the same folder and serve them from a web server (GitHub Pages works).
Opening `index.html` by double-clicking will not load the map data.

## Publish on GitHub Pages
1. Create a new, empty public repository (no README) and upload these files, or add this folder in GitHub Desktop and publish it.
2. Settings > Pages > Deploy from a branch > `main`, `/ (root)` > Save.
3. The site appears at `https://<your-username>.github.io/<repository-name>/` — this copy is live at https://shanem73.github.io/oakland-campus-atlas/.
