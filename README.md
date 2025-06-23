# Ramjet Inlet Design Optimization Project

This project focuses on the aerodynamic design and optimization of ramjet engine inlets using a combination of Python-based computational tools, machine learning models, and CFD simulation.

## Features

- Automatic `.geo` file generation for inlet geometries
- Oblique shock and normal shock calculators
- Machine learning model training and prediction using XGBoost
- CFD automation with SU2
- 3D mesh visualization using PyVista
- GUI tools built with Tkinter and PyQt5
- Export results to Excel using XlsxWriter

## Environment

- Python version: **3.10**
- OS: **Ubuntu 20.04**

## Dependencies

To install Python dependencies:

```bash
pip install -r requirements.txt
```

To run the project, you will also need to install the following external tools:

| Tool       | Version    | Description                              |
|------------|------------|------------------------------------------|
| SU2        | v8.0.1     | CFD solver used for compressible flows   |
| Gmsh       | 4.11.1     | Mesh generation from .geo files          |
| ParaView   | 5.11.1     | Visualization of CFD results             |



## Author

Süleyman Altundağ, Yunus Gözel
