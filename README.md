# SLICEM

Algorithm that takes 2D projection images (specifically class averages) from cryo-EM data of multiple macromolecular assemblies and separates them into related groups

code is currently in notebook form SLICEM.ipynb

input is zero-mean normalized 2D class averages as .mrcs and the accompanying particle.star 

output is new particle.star file for each cluster of particles to be used for 3D reconstruction

Example mrcs and star file provided, corresponding cryo-EM data at EMPIAR-10268


Link to JSB paper:
Separating distinct structures of multiple macromolecular assemblies from cryo-EM projections
https://www.sciencedirect.com/science/article/pii/S1047847719302370

Link to bioRxiv: https://www.biorxiv.org/content/10.1101/611566v1
