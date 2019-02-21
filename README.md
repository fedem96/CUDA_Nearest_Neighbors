# CUDA_Nearest_Neighbors
The aim of this project is to measure the speedup obtained for the algorithm K Nearest Neighbors when implemented in CUDA.
As comparison algorithm, the implementation in the library nanoflann was chosen.

## System configuration
+ Intel Core i7-8750h @ 2.20Ghz (up to 4.10Ghz with Turbo Boost)
+ 16 GiB RAM
+ NVIDIA GeForce GTX 1050 Ti (Notebook)
+ CUDA 10.0

## Nanoflann
The original nanoflann repository can be found here: https://github.com/jlblancoc/nanoflann

## Datasets
Sift and siftsmall datasets can be found in http://corpus-texmex.irisa.fr, where they are called ANN_SIFT1M and ANN_SIFT10K respectively.