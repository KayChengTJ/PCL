# PCL
基于PCL库的点云处理

# Dockerfile Information
Ubuntu 18.04
PCL 1.11.1
CUDA 9.2
Other lib: liblas

# Image Build Command
docker build -t ${ImageName}:${tag} --build-arg USE_CUDA=true .
OR: docker build --build-arg USE_CUDA=true -t ${ImageName}:${tag} .
