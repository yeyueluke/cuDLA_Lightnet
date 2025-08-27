# cuDLA_Lightnet


# Env


Orin


Docker image (nvcr.io/nvidia/l4t-jetpack:r36.2.0)

板子：orin 5.1.2（35.4.1） & 6.2(36.4.3）


# Dependencies


`sudo apt update`


`sudo apt install libopencv-dev python3-pip libgflags-dev git git-lfs`

For `nvsci_headers`, please you may get it from https://developer.nvidia.com/downloads/embedded/l4t/r36_release_v3.0/sources/public_sources.tbz2

https://developer.download.nvidia.cn/embedded/L4T/r35_Release_v3.1/sources/public_sources.tbz2?t=eyJscyI6IndlYnNpdGUiLCJsc2QiOiJkZXZlbG9wZXIubnZpZGlhLmNvbS9uYW5vdmRiIn0=

https://developer.download.nvidia.com/embedded/L4T/r35_Release_v5.0/sources/public_sources.tbz2?t=eyJscyI6IndlYnNpdGUiLCJsc2QiOiJkZXZlbG9wZXIubnZpZGlhLmNvbS9uYW5vdmRiIn0=

不同jetpack的 nvsci_headers 有点不一样。 项目中include 已包含 nvsci_headers ，如果有必要根据实际的jetpack版本下载


# Instructions


`bash script/build_dla.sh`   目前缺失脚本里的onnx文件


`make -j`


`make run`


# Reference


https://github.com/tier4/trt-lightnet


https://github.com/angry-crab/cudla_dev

