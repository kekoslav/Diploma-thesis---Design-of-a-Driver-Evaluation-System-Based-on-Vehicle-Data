Diploma Thesis – Design of a Driver Evaluation System Based on Vehicle Data
===========================================================================

Repository structure:
.
├── Modelovanie.ipynb        # Core modelling and scoring logic
├── Synteticke_data.ipynb    # Generation and analysis of synthetic driving data
├── Grafy_a_Tabulky.ipynb    # Visualizations, charts, and result tables
└── README.md                # Project documentation


Description:
This repository contains practical artifacts related to a diploma thesis
focused on the design of a driver evaluation and scoring system based on
data collected from connected vehicles.

The thesis addresses the problem of how to objectively assess driving
behaviour using telematics and sensor-based data while ensuring
interpretability, scalability, and practical applicability.


Thesis topic:
Design of an adaptive driver evaluation system based on vehicle data,
with emphasis on safety-related behaviour and contextual driving factors.


Problem context:
- Modern vehicles generate large volumes of telematics data
- Raw driving data are difficult to interpret without aggregation
- Existing scoring systems are often opaque or overly simplified
- There is a need for transparent, data-driven driver assessment models


Solution concept:
- Definition of safety-relevant driving indicators
- Context-aware interpretation of driving events
- Aggregation of events into composite driver scores
- Emphasis on explainability rather than black-box prediction


Notebook overview:

Modelovanie.ipynb:
- Core modelling logic
- Definition of scoring metrics and weights
- Aggregation of driving events into driver-level scores
- Evaluation of model behaviour under different assumptions

Synteticke_data.ipynb:
- Generation of synthetic driving datasets
- Simulation of driving behaviour patterns
- Validation of model robustness without sensitive real-world data

Grafy_a_Tabulky.ipynb:
- Exploratory data analysis
- Visualization of score distributions
- Comparison of drivers and scenarios
- Supporting figures and tables for the thesis text


How to run:

$ jupyter notebook Modelovanie.ipynb
$ jupyter notebook Synteticke_data.ipynb
$ jupyter notebook Grafy_a_Tabulky.ipynb

All notebooks are self-contained and rely only on standard Python
data science libraries.


Key characteristics:
- Data-driven and reproducible methodology
- No reliance on proprietary or confidential datasets
- Transparent scoring logic
- Clear separation between data, modelling, and visualization
- Designed for academic and applied research use


Limitations:
- Use of synthetic data limits direct real-world validation
- Scoring weights are partially assumption-based
- Results depend on data availability and sensor quality
- The system is a conceptual and analytical prototype


Possible extensions:
- Validation on real-world fleet or insurance data
- Integration with real-time vehicle data streams
- Machine learning-based personalization layers
- Longitudinal driver behaviour analysis
- Deployment as a backend scoring service


Author:
Kristián Marcinčák

This repository accompanies a diploma thesis and serves as a research
prototype rather than a production-ready system.
