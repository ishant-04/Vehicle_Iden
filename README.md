<p align="center">
  <h1 align="center">🚖Vehica: Vehicle classification based on RetinaNet</h1>
  <p align="center">
    <a href="LICENSE"><img src="https://img.shields.io/github/license/joey66666/vehicle-classify?color=blue&style=flat-square"></a>
    <a href="https://github.com/joey66666/vehicle-classify/"><img src="https://img.shields.io/badge/Platform-Mac%20%7C%20Windows%20%7C%20Linux%20-brightgreen?color=red&style=flat-square"></a>
    <a href="http://hits.dwyl.io/joey66666/vehicle-classify" alt="hit count"><img src="http://hits.dwyl.io/joey66666/vehicle-classify.svg?style=flat-square" /></a> 
  </p>
</p>


> Vehicle brand &amp; model classification based on [RetinaNet](https://github.com/fizyr/keras-retinanet) & [Stanford Car Dataset](https://ai.stanford.edu/~jkrause/cars/car_dataset.html)

### ✔️Feature

1. Detect vehicle in the image and mark with box. (Work on 196 brands)
2. Show the brand of the vehicle with probability.
3. Time spent during the detection.

### 👋🏻How to start
> 
> cd vehicle-classify/vehicle_UI
>
> conda install tensorflow==1.14.0 opencv numpy matplotlib keras
>
> pip install pyqt5 keras-retinanet 
> 
> cd keras_retinanet
>
> mkdir snapshots

> python vehicle_ui.py

### 📸Screenshots

<img src="pics/ui_en.png" style="zoom:50%;" />

### 📃Tips

- **It may take serval seconds to run the program related to the hardware, please wait after starting.**
- Trained Models are [here](https://github.com/joey66666/vehicle-classify/releases)

### ⚙️Dependencies 

- keras-retinanet
- Pyqt5
- Opencv
- Tensorflow
- Matplotlib

---

