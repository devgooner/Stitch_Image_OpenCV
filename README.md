# Stitching Image
This is a small C++ script that uses the OpenCV library to perform image stitching on Ubuntu.
# Data
APAP Dataset (2013): https://cs.adelaide.edu.au/~tjchin/apap/#Datasets
# Installation
- [CMake]
```
sudo apt-get install cmake
```
- [OpenCV]
```
sudo apt install libopencv-dev
```
# Using Docker
```
cd Stitch_Image_OpenCV/docker
bash ./docker_build.sh
bash ./docker_run.sh
```
# Usage
```
cd Stitch_Image_OpenCV
mkdir build
cd build
cmake ..
make -j10
./ProcessImage path_to_your_folder
```
# Example
```
./ProcessImage ./Stitch_Image_OpenCV/data
```
The image after stitching will be saved at ./Stitch_Image_OpenCV/result.jpg
<p align='center'>
    <img src="./result.jpg" alt="drawing" width="500"/>
</p>

**Thank you for accessing my repository. I wish you success.**