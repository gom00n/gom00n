### Hi, I'm Moti Gomon 👋 &nbsp;<sub>(Matvey / Motja)</sub>

GIS & cartography, with a soft spot for turning slow, manual map work into automated pipelines — and for building tools around fairly niche quizzes on the side.

I work mostly at the intersection of **historical maps, cadastral data, and computer vision**: taking scanned paper maps and land-registry documents and getting clean, georeferenced, structured data out of them.

---

### 🗺️ Featured projects

| Project | What it does | Tech |
|---------|--------------|------|
| **[AutoGeoReferencing](https://github.com/gom00n/AutoGeoReferencingPublic)** | Automatically georeferences 1940s Palestine 1:20,000 map scans. A CNN detects the printed triangulation-point symbols, matches them to a geodetic control-point database, and solves the pixel → world affine — no manual control-point picking. Best sheets land within ~6 m. | Python · PyTorch · OpenCV · EasyOCR |
| **[AutoLineDetector](https://github.com/gom00n/AutoLineDetectorPublic)** | Extracts parcel-border **lines** from scanned historical cadastral sheets and vectorizes them to georeferenced polylines — on an ArcGIS Pro *Basic* license. Skeleton-graph tracer + per-run conflation onto the modern cadastre. | Python · GDAL/OGR · scikit-image · shapely |
| **[NesahTabuParser](https://github.com/gom00n/NesahTabuParserPublic)** | Turns Israeli Land Registry PDF extracts (נסחי טאבו) into a clean Excel sheet — pulls current owners, drops canceled records, and collapses private owners to preserve privacy. | PowerShell · WinForms · pdftotext |
| **[G-index](https://github.com/gom00n/G_index)** | Computes the G-index bibliometric metric from citation data. | Python · Jupyter |

---

### 🧰 Tooling
`Python` · `PyTorch` · `OpenCV` · `GDAL/OGR` · `shapely` / `scikit-image` · `ArcGIS Pro / arcpy` · `QGIS` · `PowerShell`

### 📫 Reach me
[Telegram @motja](https://t.me/motja) · gomonmattew@gmail.com

<sub>Most repos above are public "showcase" copies — code and docs, with proprietary scans, databases, and client data intentionally excluded.</sub>
