# Nucleus–Cytoskeleton Spring Simulator

This Python script simulates a 2D mesh interacting with an elastic “nucleus” ring via springs.  
You can configure:

- **Interior springs** between mesh triangles  
- **Boundary springs** along top/bottom edges  
- **Cross–interface springs** between top/mid and bottom/mid layers  
- **Nuclear membrane + pressure** forces  
- **Nucleus↔mid tethers** (green), with optional cross‑nucleus chords  
- **Stiff auxiliary springs** (orange) that you can cut at runtime  

Results are rendered as an MPEG‑4 video plus time‑series force plots.

---

## Requirements

- Python 3.8+  
- NumPy  
- SciPy  
- Matplotlib  
- FFmpeg (for writing the `.mp4`)  

## Directory Layout
├── Mesh/
│   ├── midconf_PointsN99.txt
│   └── midconf_TrianglesN99.txt
├── nucleus_cytoskeleton_model_072225.ipynb       # Main simulation script
└── README.md                                     # You are here
