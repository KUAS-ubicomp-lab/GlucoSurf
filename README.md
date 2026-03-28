# GlucoSurf: Interactive Visualization of Glucose Dynamics

GlucoSurf is a visualization and analysis framework designed to explore glucose dynamics through intuitive and interactive representations. It enables a better understanding of temporal patterns, postprandial responses, and variability in glucose data.

Understanding glucose dynamics is essential for diabetes management, personalized health monitoring, and the design of behavioral interventions. However, traditional time-series plots often fail to capture the multi-dimensional relationships inherent in glucose data.

To address this limitation, GlucoSurf transforms glucose signals into 2D and 3D visual surfaces. These interactive visualizations allow users to manipulate the plots (e.g., rotate, zoom in/out) and examine them from multiple perspectives, which facilitate deeper insights into postprandial glucose dynamics.

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
| `3DVis_figs/`  | Interactive 3D glucose surface visualizations |
| `.gitignore`    | Specifies files ignored by Git |
| `GlucoSurf.ipynb`   | Main notebook for data preprocessing and visualization generation |
| `LICENSE`    | Project license |
| `README.md`    | Project documentation |

This study utilized the [BIG IDEAs dataset](https://www.nature.com/articles/s41746-021-00465-w). Due to copyright restrictions, the dataset is not included in this repository. The data can be accessed and downloaded from [PhysioNet](https://physionet.org/content/big-ideas-glycemic-wearable/1.1.2/). 

## Research Context

This project is part of ongoing research on:

- Wearable-based health monitoring
- AI-driven physiological modeling
- Human-centered visualization of biomedical data

The goal is to bridge data-driven insights and user-understandable representations for real-world health applications.

## Citation
If you use this project in your research, please cite:

Liang Z,  Lococo M, Karunarathna TS. (2026) [Visual Analytics of Sugar Intake and Postprandial Interstitial Glucose Dynamics Using 3D Surface Plots](https://www.researchgate.net/publication/401828019_Visual_Analytics_of_Sugar_Intake_and_Postprandial_Interstitial_Glucose_Dynamics_Using_3D_Surface_Plots). In Proceedings of The The 10th International Conference on Medical and Health Informatics (ICMHI 2026), Kyoto, Japan.

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
