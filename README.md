# ÅBIM — OpenBIM Web Application for 4D/5D Project Management
> **Research project** · MSc Thesis · EC³ 2026 Paper · Developed with [IfcOpenShell](https://ifcopenshell.org) + [ThatOpen Engine](https://thatopen.com)
The AEC industry loses billions yearly to fragmented workflows: schedules in MS Project, costs in Excel, models in Revit — never talking to each other. ÅBIM proposes a different approach: using the IFC schema as the single source of truth for 4D scheduling, 5D cost estimation, and resource allocation — entirely within the OpenBIM ecosystem, without proprietary silos.
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
The framework operates in a decoupled architecture: IFC data is enriched programmatically and written back into the schema, independent of any authoring software. All scheduling, cost, and resource data live natively inside the IFC file — queryable, portable, and auditable.
---
## Academic context
📄 Accepted paper — EC³ 2026 (European Conference on Computing in Construction) - Corfu, Greece · July 12–15, 2026
> *"Project Management with IFC: Toward an Open-BIM Framework"*  
> Padoan R., Pinti L., Karlshøj J. — University of Trento, Technical University of Denmark
The paper introduces the methodology behind ÅBIM and validates the framework against a real construction model, demonstrating automated 4D/5D enrichment of IFC entities with full traceability.
---
## Research gap addressed
Current tools treat IDS validation, scheduling, and cost estimation as isolated processes, consistently replaced by proprietary tools that fragment data and never write it back into the schema. ÅBIM demonstrates that `IfcWorkPlan`, `IfcCostSchedule`, and `IfcConstructionResource` can be synchronized in a single open-source pipeline — moving toward the "Total BIM" vision where the digital model is the primary contractual record.
---
## Repository structure
This is a showcase repository (demo videos + documentation). The core application is under a Demonstration-Only Proprietary License pending thesis submission.
---
## Author
**Riccardo Padoan** — MSc Civil Engineering, University of Trento · Erasmus+ at DTU  
📩 [E-mail](mailto:riccardopadoan28@gmail.com)· 💼 [LinkedIn](https://www.linkedin.com/in/riccardopadoan00/)

