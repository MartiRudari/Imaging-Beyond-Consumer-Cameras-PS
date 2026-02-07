# Imaging-Beyond-Consumer-Cameras-PS
# NeRF-pytorch Implementation (Google Colab)
This project implements Neural Radiance Fields (NeRF) using PyTorch and Google Colab. The goal of this project is to reconstruct 3D scenes from 2D images and generate novel viewpoints using neural rendering techniques.
The implementation is inspired by the official PyTorch Implementation by yenchenlin/nerf-pytorch.

# References
NeRF paper: NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis: Ben Mildenhall, Pratul P. Srinivasan, Matthew Tancik, Jonathan T. Barron, Ravi Ramamoorthi, Ren Ng, 2020.
Implementation inspiration: https://github.com/yenchenlin/nerf-pytorch

# Experiments
The NeRF model was trained and evaluated on synthetic datasets: Chair and Lego
The datasets provide clean, noise-free rendered images. The trained model successfully generated novel views of the scenes.

# Real World datasets
Additional experiments were performed using a real captured dataset: T-Rex and Pinecone(360° dataset).
Compared to synthetic datasets, the real-world datasets are more challenging due to lighting variations, camera calibration imperfections, image noise, and more complex scenes. The results show that these datasets require longer training times to achieve higher quality reconstructions. 

# Results
The project generates rendered sequences showing novel view synthesis from trained NeRF models. Output videos are generated in mp4 format.

# Running the project
The project was developed and executed using Google Colab
1. Open the notebook available in this repository, and mount your own Google Drive.
2. Dataset paths may need to be adjusted depending on the user's directory structure.
3. Dataset used: Synthetic Chair and Lego, Real-World Trex and Pinecone 360°

# Future improvements
Longer training and faster NeRF variant testing (Instant-NGP)
