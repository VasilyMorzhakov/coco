# MS COCO API - http://mscoco.org/

Microsoft COCO is a large image dataset designed for object detection, segmentation, and caption generation. This package provides Matlab, Python, and Lua APIs that assists in loading, parsing, and visualizing the annotations in COCO. Please visit http://mscoco.org/ for more information on COCO, including for the data, paper, and tutorials. The exact format of the annotations is also described on the COCO website. The Matlab and Python APIs are complete, the Lua API provides only basic functionality.

In addition to this API, please download both the COCO images and annotations in order to run the demos and use the API. Both are available on the project website.
-Please download, unzip, and place the images in: coco/images/
-Please download and place the annotations in: coco/annotations/
For substantially more details on the API please see http://mscoco.org/dataset/#download.


## Install

    sudo apt-get install python3-dev
    pip install cython
    pip install git+git://github.com/waspinator/coco.git@2.1.0

