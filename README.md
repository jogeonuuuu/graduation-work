pip install https://developer.download.nvidia.com/compute/redist/jp/v511/pytorch/torch-2.1.0a0+41361538.nv23.06-cp38-cp38-linux_aarch64.whl

pip install https://github.com/ultralytics/assets/releases/download/v0.0.0/torchvision-0.16.2+c6f3977-cp38-cp38-linux_aarch64.whl

sudo apt-get install -y libjpeg-dev zlib1g-dev

python -c "import torch; print(torch.__version__)"
python -c "import torchvision; print(torchvision.__version__)"
