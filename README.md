[![Build Status](https://travis-ci.org/rportugal/opencv-zbar.svg?branch=master)](https://travis-ci.org/rportugal/opencv-zbar)

## Description
Barcode and QR Code reader using OpenCV and ZBar

macOS users can simply install using Homebrew

    brew install zbar
Ubuntu users can install using

    sudo apt-get install libzbar-dev libzbar0

After installing ZBar and OpenCV...

    mkdir build
    cd build
    cmake ..
    make
    ./zbar_opencv
