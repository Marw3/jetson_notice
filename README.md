# jetson_notice
Problems and solutions for jetson devices


---- torch.cuda.is_available() = False (https://forums.developer.nvidia.com/t/pytorch-for-jetson-version-1-11-now-available/72048)

wget https://nvidia.box.com/shared/static/p57jwntv436lfrd78inwl7iml6p13fzh.whl -O torch-1.8.0-cp36-cp36m-linux_aarch64.whl

sudo apt-get install python3-pip libopenblas-base libopenmpi-dev libomp-dev

pip3 install Cython

pip3 install numpy torch-1.8.0-cp36-cp36m-linux_aarch64.whl
