# Implementation of real-time face recognition based on CNN on PYNQ Z2
[*Demo Video*](https://youtu.be/rNg161h5d7w "Demo Video")	

`This project was started in 2022.02 and finished in 2022.06.`
## Content
* [Abstract](#abstract)
* [Preparation](#preparation)
* [Approach](#approach)
* [How to Reproduce](#how-to-reproduce)
* [Thanks](#thanks)

## Abstract
Independently implement a real-time face recognition Python project based on CNN convolutional neural network to display and label the captured real-time images and face recognition results on the monitor. Score: 95/100. 

## Preparation
- PYNQ Z2 board
- USB Webcam
- Monitor
- A computer with Jupyter Notebook

## Approach
1. Import all packages needed. Download the bitstream.
2. Configure the video in/out and HDMI in/out.
3. Load and encode the pictures.
4. Detect and recognize the faces.
5. Release the cache and memory.

## How to Reproduce
1. Download the file [code.ipynb](/code.ipynb).
2. Turn on the PYNQ Z2 board; USB webcam; monitor. And make sure all components work well.
3. Run the code.

## Thanks
- Many, many thanks to my teacher, Prof. Pan.
- Thanks to TA, Dr. Wang and Dr. Huang.
