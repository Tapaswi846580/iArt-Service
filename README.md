# iArt-Service
A web service created in python using Flask for [iArt project](https://github.com/Tapaswi846580/iArt)<br>
Developed by [Tapaswi Satyapanthi](https://www.linkedin.com/in/tapaswi97/)

As the file size of some files exceeds the github's maximum file size(100 mb) I have kept this project on the **Google Drive**<br>
Please refer the **Getting Started** Section in order to download the project required libraries.

## Getting started
- Download this project from [here](https://drive.google.com/open?id=11jdUpzymmc9p1scQrhOOFFx9cET12wWY)
- [Requirements](#requirements)
- [Starting the service](#starting-the-service)
- [Credits and References](#credits-and-references)


### Requirements
#### 1. [Python '3.7.5'](https://www.python.org/downloads/release/python-375/)
#### 2. [Tensorflow](https://www.tensorflow.org/)<br>
If you are using Tensorflow 1.0 then replace the following lines

```python
import tensorflow.compat.v1 as tf
tf.disable_v2_behavior()
```
with
```python
import tensorflow as tf
```
from ```service.py```, ```src > transform.py``` and ```src > vgg.py```<br>

If you are using tensorflow 2.0 then keep everything as it is.<br>
As I was using Tensorflow 2.0 for other projects but for this project it requires tensorflow 1.0 so I have imported tensorflow version 1 and used its behaviour.

#### 3. [Flask '1.1.1'](https://pypi.org/project/Flask/1.1.1/)
#### 4. [Pillow '6.2.0'](https://pypi.org/project/Pillow/6.2.0/)
#### 5. [OpenCV '4.1.1'](https://docs.opencv.org/4.1.1/)
#### 6. [Scipy '1.1.0'](https://pypi.org/project/scipy/1.1.0/)
#### 7. [Numpy '1.17.4'](https://pypi.org/project/numpy/1.17.3/)

## Starting the service
After installing all the requirments browse to the project directory and simply run the ```service.py``` by double clicking on the file or by command ```python service.py```


## Credits and References
This project could not have happened without the help of [Logan Engstrom](https://github.com/lengstrom) and [Adrian Rosebrock](https://www.pyimagesearch.com/author/adrian/).<br>
- For detailed description regarding **Image style transfer** visit [Logan Engstrom's repository](https://github.com/lengstrom/fast-style-transfer) on Fast Style Transfer.
- For detailed description about **Image colorization** visit [Adrian Rosebrock' post](https://www.pyimagesearch.com/2019/02/25/black-and-white-image-colorization-with-opencv-and-deep-learning/) on Black and white image colorization with OpenCV and Deep Learning.
- For the output of this project visit my iOS application project [iArt](https://github.com/Tapaswi846580/iArt).
