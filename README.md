## Helemet Detection

This project used [Darkflow](https://github.com/thtrieu/darkflow) which does Real-time object detection and classification based of YOLO (in darknet). Paper: [version 1](https://arxiv.org/pdf/1506.02640.pdf), [version 2](https://arxiv.org/pdf/1612.08242.pdf).

Demo of Darkflow: [Imgur link](http://i.imgur.com/EyZZKAA.gif)

<p align="center"> <img src="demo.gif"/> </p>

## Compatibility & Dependencies
> I've updated the darkflow to make it compatible with versions post the ```Tensorflow 2.x``` upgrade.

#### Python3, tensorflow 2.x, numpy, opencv 3, Cython.

## Getting started

1. Clone the repository and ``` cd ``` in to the directory
2. Build the darkflow Cython extensions in place. 
``` 
python3 setup.py build_ext --inplace
```
3. Download weight files
[Weight file link](https://drive.google.com/file/d/1oH9f94nYlnkT15amplhPv9uOTWZjamIS/view)

4. Create a new directory/ folder called bin and paste the weight file inside ```bin```
5.
```
python3 detection.py
```

That's all you are good to go :)