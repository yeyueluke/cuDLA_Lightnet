# cuDLA_Lightnet


# Env


Orin


Docker image (nvcr.io/nvidia/l4t-jetpack:r36.2.0)

板子：orin 5.1.2（35.4.1） & 6.2(36.4.3）


# Dependencies


`sudo apt update`


`sudo apt install libopencv-dev python3-pip libgflags-dev git git-lfs`

For `nvsci_headers`, please you may get it from https://developer.nvidia.com/downloads/embedded/l4t/r36_release_v3.0/sources/public_sources.tbz2


# Instructions


`bash script/build_dla.sh`   目前缺失脚本里的onnx文件


`make -j`


`make run`


# Reference


https://github.com/tier4/trt-lightnet


https://github.com/angry-crab/cudla_dev

