# object-detection
Simple trial code for AAT object detection project. Based on [Tensorflow object detection model](https://github.com/tensorflow/models/tree/master/research/object_detection), picked out the key code and did some modifications, visualized the counting data to the video screen.

## Preview
![gif](https://github.com/sjhhh3/object-detection/blob/master/sample.gif)

## Dependencies

Tensorflow Object Detection API depends on the following libraries:

*   Protobuf 3.0.0
*   Python-tk
*   Pillow 1.0
*   lxml
*   tf Slim (which is included in the "tensorflow/models/research/" checkout)
*   Jupyter notebook
*   Matplotlib
*   Tensorflow (>=1.12.0)
*   Cython
*   contextlib2
*   cocoapi

For detailed steps to install Tensorflow, follow the [Tensorflow installation
instructions](https://www.tensorflow.org/install/). A typical user can install
Tensorflow using one of the following commands:

``` bash
# For CPU
pip install tensorflow
# For GPU
pip install tensorflow-gpu
```

The remaining libraries can be installed on Ubuntu 16.04 using via apt-get:

``` bash
sudo apt-get install protobuf-compiler python-pil python-lxml python-tk
pip install --user Cython
pip install --user contextlib2
pip install --user jupyter
pip install --user matplotlib
```

Alternatively, users can install dependencies using pip:

``` bash
pip install --user Cython
pip install --user contextlib2
pip install --user pillow
pip install --user lxml
pip install --user jupyter
pip install --user matplotlib
```
