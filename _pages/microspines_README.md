---
permalink: /microspines
title: "Compliant Microspine Arrays for Soft Robots"
author_profile: true
---


[![Paper](https://img.shields.io/badge/ICRA%202025-Paper-blue)](https://ieeexplore.ieee.org/document/11128855)
[![arXiv](https://img.shields.io/badge/arXiv-2502.12347-b31b1b.svg)](https://arxiv.org/abs/2502.12347)
[![Patent](https://img.shields.io/badge/Patent-US%2063%2F711%2C508-green)](https://patents.google.com/)
[![Best Paper](https://img.shields.io/badge/ICRA%202025-Best%20Paper%20Award-gold)](https://softroboticsforspace.eu/best-paper-award)

Visit the [Github repository](https://github.com/lefaris/microspines) for additional supplemental data and 
processing code for **"Improving Grip Stability Using Passive Compliant Microspine Arrays for Soft Robots in Unstructured Terrain"** presented at IEEE ICRA 2025.

**Best Paper Award** at ICRA 2025 Workshop on Soft Robotics for Space Applications

---

![Microspines Demo](images/microspines/microspines.gif)


## Overview

This repository contains experimental data and visualization code supporting our research on improving locomotion capabilities of soft robots through passive compliant microspine arrays. Microspine grippers are bio-inspired mechanisms that engage with surface asperities to increase shear force and traction. While soft robots are ideal candidates for complex terrain due to their conformability, they historically struggle with grip stability and efficient locomotion outside controlled lab environments. Our work addresses the real-world deployment gap for soft robotics by enabling reliable traversal of unstructured terrain.

### Key Contributions

1. **Novel Design:** Two-row stacked microspine array utilizing independent compliant mechanisms for enhanced grip 
   stability
2. **Simplified Control:** Single actuator controls entire array through intelligent soft-compliant integration
3. **Field Validation:** Experimental testing on four real-world surfaces with varying surface topographies (concrete, 
   brick, sand, forest floor)
4. **Quantified Performance:** Demonstrated 18-25x improvement in displacement over baseline soft robots
5. **Patent Application:** USPTO Application No. 63/711,508

---

## Repository Contents

```
microspines/
├── data/                           # Experimental tracking data
│   └── [Surface-specific datasets with AprilTag results]
├── data_analysis/                  # Displacement/consistency metrics
└── media/                          # Figures and visualizations
```

### Data Processing Scripts

#### `microspine_bar_chart.py`
Generates comparative bar charts showing average displacement across robot configurations (0ML, 1ML, 2ML) and surface types. Includes standard deviation error bars for statistical analysis.

**Usage:**
```python
python microspine_bar_chart.py
```

#### `microspines_ellipse.py`
Visualizes gait trajectories as ellipses, illustrating the cyclic nature of locomotion and comparing movement patterns across different microspine configurations.

**Usage:**
```python
python microspines_ellipse.py
```

---

## Experimental Setup

### Robot Configurations

- **0ML (Baseline):** Aqua soft robot without microspines
- **1ML:** Soft robot with 10 microspines in one array on a single limb
- **2ML:** Soft robot with 20 microspines in two arrays on two opposing limbs

### Test Surfaces

1. **Uniform Concrete:** Level surface with consistent asperity distribution
2. **Partially Uniform Brick:** Structured but irregular surface texture along brick perimeters
3. **Granular Compact Sand:** Loose top layer over compact base with scattered debris
4. **Forest Floor:** Highly unstructured terrain with large tree roots, leaves, and debris

### Tracking Methodology

- **Marker System:** 36h11 family AprilTags attached to each limb
- **Trials:** 3 trials per configuration per surface (36 total trials)
- **Gaits per Trial:** 60 push-pull gaits
- **Total Gaits Analyzed:** 2,160 gaits across all experiments

---

## Key Results

### Displacement Performance

| Surface | 0ML (Baseline) | 1ML                              | 2ML                          |
|---------|----------------|----------------------------------|------------------------------|
| Concrete | *1.32cm*       | **39.63cm** (>30x improvement)   | 14.13cm (>10x improvement)   |
| Brick | *0.59cm*       | **15cm** (>25x improvement)      | 10.52cm (>18x imrpovement)   |
| Sand | 0.82 cm        | **2.53 cm** (>3x improvement)    | *0.46 cm**                   |
| Forest Floor | *13.74cm*      | **23.95cm** (~1.75x improvement) | 21.32cm (~1.55x improvement) |

*Note: 2ML dug deeper into loose sand, resulting in slight burrowing and lower displacement on this specific surface.

### Critical Findings

- **Microspine arrays enable traversal of obstacles** (4" tree roots) that the baseline robot could not overcome on 
  the forest floor
- **Microspine array design provides redundancy** - not all microspines need to engage for effectiveness
- **Passive compliance allows stuck microspines to wiggle free** without hindering overall movement
- **Bottom row spines activate on uniform terrain**, top row engages on highly irregular surfaces

---

## Citation

If you use this data or build upon our work, please cite:

```bibtex
@inproceedings{ervin2025microspines,
  title={Improving Grip Stability Using Passive Compliant Microspine Arrays for Soft Robots in Unstructured Terrain},
  author={Ervin, Lauren and Bezawada, Harish and Vikas, Vishesh},
  booktitle={IEEE International Conference on Robotics and Automation (ICRA)},
  year={2025},
  organization={IEEE},
  doi={10.1109/ICRA55743.2025.11128855}
}
```

**arXiv preprint:** [arXiv:2502.12347](https://arxiv.org/abs/2502.12347)

---

## Patent Information

**Title:** Compliant Mechanism Microspines for Mobile Soft Robots  
**Application No.:** US 63/711,508  
**Filing Date:** October 24, 2025  
**Inventors:** Lauren Ervin and Vishesh Vikas  
**Status:** Pending


---

## Updates

- **October 2025:** Patent application filed (US 63/711,508)
- **September 2025:** Paper published on IEEE Xplore in IEEE ICRA 2025 proceedings
- **May 2025:** Best Paper Award at ICRA 2025 Workshop
- **January 2025:** Paper accepted to IEEE ICRA 2025

---

## License

This project is released for academic and research purposes. For commercial applications related to the patented technology, please contact the inventors.
