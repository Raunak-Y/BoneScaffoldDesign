# Novel Organic Biomimetic Lattice Structures for Bone Analogous Applications

## Overview
This repository contains the design, analysis, and evaluation of biomimetic lattice structures for bone scaffold applications, specifically targeting the femoral diaphysis. The project addresses the critical challenge of stress shielding in orthopaedic implants by developing lattice-based scaffolds with mechanical properties closer to natural bone.

## Problem Statement
Conventional orthopaedic implants made from dense metallic materials possess significantly higher stiffness than human bone, leading to:
- **Stress shielding**: Uneven load distribution causing bone resorption
- **Implant failure**: Weakening of the bone-implant interface
- **Poor biological integration**: Inadequate pore structure for tissue growth

## Objectives
- Design and model lattice-filled cylindrical specimens representing simplified femoral diaphysis segments
- Compare four lattice topologies: Simple Cubic (SC), Body-Centered Cubic (BCC), Face-Centered Cubic (FCC), and Fluorite
- Analyze the effect of strut thickness (0.75mm and 1.0mm) on mechanical behavior
- Compute effective Young's modulus using deformation-based homogenization
- Identify lattice structures matching cortical bone properties (17-20 GPa)

## Methodology
### Geometric Model
- **Specimen Dimensions**: 20mm diameter × 20mm length cylindrical models
- **Lattice Topologies**: SC, BCC, FCC, Fluorite
- **Strut Thickness**: 0.75mm and 1.0mm
- **Total Configurations**: 8 (4 topologies × 2 thicknesses)

### Analysis
- **Software**: nTopology for lattice generation and FEA
- **Material**: Structural steel (E = 200 GPa, ν = 0.3)
- **Loading**: 500N compressive load on top surface
- **Boundary Conditions**: Fixed bottom surface

### Effective Young's Modulus Calculation
