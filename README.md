### Hi, I'm Moti Gomon 👋 &nbsp;<sub>(Matvey / Motja)</sub>

GIS & cartography, with a soft spot for turning slow, manual map work into automated pipelines — and for building tools around fairly niche quizzes on the side.

I work at the intersection of **historical maps, cadastral data, and computer vision**. My current work is a national cadastral map-digitization project: I ran the pipeline by hand first — scanning, georeferencing, digitizing, land-registry processing — and then replaced the slow parts with the tools below. Two of them now run in daily production.

---

### 🛰️ Professional — GIS, maps & data automation

| Project | What it does | Tech |
|---------|--------------|------|
| **[AutoLineDetector](https://github.com/gom00n/AutoLineDetectorPublic)** | **In production.** Extracts parcel-border **lines** from scanned historical cadastral sheets and vectorizes them to georeferenced polylines — on a standard ArcGIS Pro license, no Spatial Analyst. Adaptive ink detection, a custom skeleton-graph tracer, and per-run conflation onto the modern cadastre. | Python · GDAL/OGR · scikit-image · shapely |
| **[NesahTabuParser](https://github.com/gom00n/NesahTabuParserPublic)** | **In daily production.** Turns a folder of Israeli Land Registry PDF extracts (נסחי טאבו) into one clean Excel table of current owners — drops canceled records, keeps public bodies by name, collapses private individuals to preserve privacy. Human-in-the-loop: anything ambiguous is flagged for review, not guessed. | PowerShell · WinForms · pdftotext |
| **[AutoGeoReferencing](https://github.com/gom00n/AutoGeoReferencingPublic)** | **Research prototype.** Georeferences 1940s Palestine 1:20,000 map scans with no manual control points: a CNN detects the printed triangulation symbols, OCR reads the margin grid labels, and RANSAC solves the pixel-to-world transform. Within ~6 m on the best sheets, with an honest per-sheet benchmark of where it fails. | Python · PyTorch · OpenCV · EasyOCR |

### 🎲 Hobby — quizzes, data toys & web experiments

| Project | What it does | Tech |
|---------|--------------|------|
| **[Country Age Map](https://github.com/gom00n/CountriesAge)** | Interactive world map colouring every country by its "age" — first sovereignty, last freed from foreign rule, or current regime date. | JavaScript · Leaflet |
| **[As_long_as](https://github.com/gom00n/As_long_as)** | Puts historical durations in perspective — pick an event and see which of 100+ others (wars, pandemics, presidencies, tech milestones) lasted just as long, or compare custom date ranges. | JavaScript · HTML |
| **[QRLife](https://github.com/gom00n/QRLife)** | Turns any link or text into a QR code, then animates it with Conway's Game of Life — a static, dependency-free browser toy. | JavaScript · HTML/CSS |
| **[G-index](https://github.com/gom00n/G_index)** | An h-index-style ranking metric for quiz players, computed from a games database — because ordinary win counts reward showing up, not consistency. | Python · Jupyter · SQLite |

---

### 🧰 Tooling
`Python` · `ArcGIS Pro / arcpy` · `QGIS` · `GDAL/OGR` · `GeoPandas` · `shapely` / `scikit-image` · `PyTorch` · `OpenCV` · `SQL` · `AutoCAD / DXF interop` · `PowerShell`

### 📫 Reach me
[LinkedIn](https://www.linkedin.com/in/matvey-gomon) · [Telegram @motja](https://t.me/motja) · gomonmattew@gmail.com

<sub>The professional repos are public "showcase" copies — code and docs only, with proprietary scans, databases, model weights and client data intentionally excluded.</sub>
