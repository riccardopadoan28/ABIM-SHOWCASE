# ÅBIM — OpenBIM Web Application for 4D/5D Project Management
> **Research project** · MSc Thesis · EC³ 2026 Paper · Developed with [IfcOpenShell](https://ifcopenshell.org) + [ThatOpen Engine](https://thatopen.com)
> The AEC industry loses billions yearly to fragmented workflows: schedules in MS Project, costs in Excel, models in Revit — never talking to each other. ÅBIM proposes a different approach: using the IFC schema as the single source of truth for 4D scheduling, 5D cost estimation, and resource allocation — entirely within the OpenBIM ecosystem, without proprietary silos.
---
## What it does
- 3D Viewer:	Browser-native rendering via WebAssembly + Three.js (ThatOpen Engine)
- IDS Auditor: Automated compliance checks against XML-based information requirements
- BCF Exporter Issue tracking exportable to any BIM authoring tool
- Quantity Take-Off and Pset extraction
- 4D Scheduling
- 5D Cost	Estimation
- PERT Analysis: Probabilistic duration estimation using beta distribution for CPM
- Resource Allocation linked to tasks
- Gantt + Cash Flow	Interactive Plotly charts
---
## 🚀 Demo
### IFC Import & 3D Viewer
[![Watch Demo](https://img.shields.io/badge/▶%20Watch%20Video-0366d6?style=for-the-badge)](https://drive.google.com/file/d/1WY8_Oiq-6LDbX3ckgpDReq56-EBziAJ4/view?usp=drive_link)
### QTO, 4D Scheduling & 5D Cost Estimation
[![Watch Demo](https://img.shields.io/badge/▶%20Watch%20Video-0366d6?style=for-the-badge)](https://drive.google.com/file/d/1MV1SRTIMlINiMYhScjQdRXeEjUwgZTYB/view?usp=drive_link)
### Gantt & Cash Flow Analysis
[![Watch Demo](https://img.shields.io/badge/▶%20Watch%20Video-0366d6?style=for-the-badge)](https://drive.google.com/file/d/19p5jFV3pBzXSbQ2MJly8Dz6yZFaZS66c/view?usp=drive_link)
> 💡 *Screenshots/GIFs coming soon*
---
## Technical stack
```
Python 3.10+  ·  IfcOpenShell 0.8.4  ·  Streamlit  ·  Pandas / NumPy
ThatOpen Engine (Three.js + WASM)  ·  Plotly  ·  IDS / BCF  ·  Git
```
### The framework operates in a decoupled architecture: IFC data is enriched programmatically and written back into the schema, independent of any authoring software. All scheduling, cost, and resource data live natively inside the IFC file — queryable, portable, and auditable.
---
## Academic context
📄 Accepted paper — EC³ 2026 (European Conference on Computing in Construction) - Corfu, Greece · July 12–15, 2026
> *"Project Management with IFC: Toward an Open-BIM Framework"*  
> Padoan R., Pinti L., Karlshøj J. — University of Trento, Technical University of Denmark
> Abstract: Successful construction management relies on interoperability, accurate cost estimation and scheduling. While OpenBIM aims to standardize workflows, current industry practices still suffer from fragmented processes and data loss, due to proprietary silos and a lack of an automated and standardized process. This research proposes a computational framework to optimize 4D and 5D BIM workflows by enriching the IFC schema. Through IfcOpenShell, the methodology enhances a standardized environment for semantic validation through IDS and collaboration through BCF, facilitating the extraction of properties and quantities, project scheduling, cost estimation and resource allocation. Results indicate that an integrated OpenBIM framework using the Industry Foundation Class (IFC) as single source of truth suggests the potential to improve reliability. The contribution is a reproducible, opensource framework that overcomes limitations providing a robust methodology for multi-dimensional BIM management.
---
## Repository structure
### This is a showcase repository (demo videos + documentation). The core application is under a Demonstration-Only Proprietary License pending thesis submission.
---
## Author
### **Riccardo Padoan** — MSc Civil Engineering, University of Trento · Erasmus+ at DTU  
### 📩 [E-mail](mailto:riccardopadoan28@gmail.com)· 💼 [LinkedIn](https://www.linkedin.com/in/riccardopadoan00/)

