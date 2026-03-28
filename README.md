# GlucoSurf: Interactive Visualization of Glucose Dynamics

GlucoSurf is a visualization and analysis framework designed to explore glucose dynamics through intuitive and interactive representations. It enables better understand temporal patterns, postprandial responses, and variabilityin glucose data. Understanding glucose dynamics is important for diabetes management, personalized health monitoring, and behavioral intervention design. However, traditional time-series plots often fail to capture multi-dimensional relationships in glucose data. GlucoSurf addresses this by transforming glucose signals into interpretable 2D/3D visual surfaces, which enables deeper insights into physiological processes.

## Features

- Interactive visualization
  - Explore glucose trajectories in 2D/3D space  
  - Visualize temporal and postprandial patterns
  
  <img width="1248" height="1200" alt="sugarGlucose_2D" src="https://github.com/user-attachments/assets/d9c0b9dd-bdaa-434b-b89a-51858a3d1a7c" />

  <img width="733" height="304" alt="glucose_sugar_all" src="https://github.com/user-attachments/assets/5ff94866-324a-48a9-a903-7053b89834aa" />

- Pattern discovery
  - Identify circadian patterns related to glucose fluctuations

  <img width="750" height="245" alt="glucose_sugar_circadian" src="https://github.com/user-attachments/assets/d1258464-c661-4ff5-8f9d-7c1e57af7f73" />

  - Analyze variability across individuals and conditions
  
  <img width="1500" height="1920" alt="subject_allData_birdview" src="https://github.com/user-attachments/assets/c5dcab6a-814b-439a-bfc4-efce5404866c" />

## Repository Structure

| Folder/File      | Description |
|----------------|------------|
| `3DVis_figs/`  | 3D glucose surface visualizations |
| `.gitignore`    | Specifies files ignored by Git |
| `GlucoSurf.ipynb`   | Main notebook for data preprocessing and visualization generation |
| `LICENSE`    | Project license |
| `README.md`    | Project documentation |

## Research Context

This project is part of ongoing research on:

- Wearable-based health monitoring
- AI-driven physiological modeling
- Human-centered visualization of biomedical data

The goal is to bridge data-driven insights and user-understandable representations for real-world health applications.

## Citation
If you use this project in your research, please cite:
```
Liang Z,  Lococo M, Karunarathna TS. (2026) Visual Analytics of Sugar Intake and Postprandial Interstitial Glucose Dynamics Using 3D Surface Plots. In Proceedings of The The 10th International Conference on Medical and Health Informatics (ICMHI 2026), Kyoto, Japan.
```

### BibTeX
```bibtex
@inproceedings{liang2026glucosurf,
  title={Visual Analytics of Sugar Intake and Postprandial Interstitial Glucose Dynamics Using 3D Surface Plots},
  author={Liang, Zilu and Lococo, Marco and Karunarathna, Thilini S.},
  booktitle={Proceedings of the 10th International Conference on Medical and Health Informatics (ICMHI 2026)},
  year={2026},
  address={Kyoto, Japan}
}
```

## Contributing
We welcome contributions!
1. Fork the repository
2. Create a new branch
3. Submit a pull request
