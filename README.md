## Directory Structure
The **Model** folder contains the RBMK core model in a jupyter notebook file
The **Analysis** folder will contain the analysis to be performed on the core

```
License
README.md
|-- Model/
|   |--RBMK_Lattice.ipynb
|-- Analysis/
```

## Instructions
The model should be able to be run as long as the user has installed openmc and it is running properly. The model is a jupyter notebook file and it is intended to be run in jupyter notebook. The model currently produces the component and core geometries.

## References
The geometry of this model is based off of dimensions from a paper looking into the design features and reasons for accident

Malko, Mikhail. The Chernobyl Reactor: Design Features and Reasons for Accident. NSRG, 2016. https://www.rri.kyoto-u.ac.jp/NSRG/reports/kr79/kr79pdf/Malko1.pdf

The core lattice arrangement comes from the paper A simplified analysis of the Chernobyl Accident.

Mercier, B., Yang, D., Zhuang, Z., & Liang, J. (n.d.). A simplified analysis of the Chernobyl accident. ScienceDirect. https://www.sciencedirect.com/org/science/article/pii/S2491929221000078
