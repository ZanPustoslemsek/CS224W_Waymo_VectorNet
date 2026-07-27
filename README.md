# CS224W Waymo VectorNet
 
A Google Colab implementation of **VectorNet**, built as part of the Stanford CS224W project *"Prediction of Agent Trajectories on the Waymo Open Dataset"* (FRI, University of Ljubljana).
 
[Project blog post](https://medium.com/@radovicevic.erik1/13ca1a79693d)
 
VectorNet encodes agent trajectories and map features as polylines, then models scene-level interactions via a global attention graph to predict future agent trajectories, following [Gao et al., 2020](https://arxiv.org/abs/2005.04259).
 
This model was adapted into the `src/vectornet/` module of the full project pipeline:
 
[radov02/Waymo-GNN](https://github.com/radov02/Waymo-GNN)
 
## Contents
 
- [`vectorNet.ipynb`](./vectorNet.ipynb) — Colab notebook with the VectorNet implementation (polyline encoding, global interaction graph, trajectory decoding).
## Usage
 
Open `vectorNet.ipynb` in Google Colab, set the runtime to GPU, and run the cells top to bottom.
