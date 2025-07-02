# TrajLens: Visual Analysis for Constructing Cell Developmental Trajectories in Cross-Sample Exploration

## Introduction

Constructing cell developmental trajectories is a critical task in single-cell RNA sequencing (scRNA-seq) analysis, enabling the inference of potential cellular progression paths. However, current automated methods are limited to establishing cell developmental trajectories within individual samples, necessitating biologists to manually link cells across samples to construct complete cross-sample evolutionary trajectories that consider cellular spatial dynamics. This process demands substantial human effort due to the complex spatial correspondence between each pair of samples.
To address this challenge, we first proposed a Graph Neural Network (GNN)-based model to predict cross-sample cell developmental trajectories. We then developed **TrajLens**, a visual analytics system designed to support biologists in exploring and refining these trajectories based on predicted links.

## Features

- **Cross-Sample Prediction Model**: Utilizes a GNN-based approach to predict cell developmental trajectories across multiple samples.
- **Visualization Integration**: Integrates features on cell distribution and developmental direction across multiple samples, providing an overview of the spatial evolutionary patterns of cell populations along trajectories.
- **Enhanced Data Interpretation**: Includes contour maps superimposed on the original cell distribution data, facilitating intuitive exploration by biologists.## System Overview

![](\figs\overview.png)
  
  **TrajLens** comprises four coordinated views designed to support the visual exploration and refinement of cross-sample cell developmental trajectories:
  **(A) Core Cell Selection View**: This view enables users to identify and select core cell types by examining their temporal occurrence and quantitative dynamics throughout development. It provides an overview of cell population changes across samples, guiding the selection of biologically meaningful reference cell types for trajectory construction.
  **(B) Path Selection View**: Designed to facilitate the intuitive selection and analysis of complex developmental paths, this view emphasizes high-frequency and diverse trajectory patterns. Users can explore potential developmental routes and focus on those with significant biological relevance.
  **(C) Path Inspection View**: This view supports in-depth inspection of spatial evolutionary patterns through a multi-row synchronized visualization. It enables comprehensive validation of developmental relationships via integrated tools for sequence inspection, single-sample analysis, and similarity assessment across samples.
  **(D) Gene Function View**: This component reveals key gene functions associated with identified developmental sequences. By linking trajectory patterns to functional annotations, it supports the biological interpretation of observed cellular transitions.
## Supplemental Materials
  
  All supplemental materials, including dataset descriptions and extended results, are available.
