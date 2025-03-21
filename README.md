# Wheat Fusarium Head Blight resistance evaluation platform

Shuchen Liu (柳书臣) <sup>1</sup>, Jie Jie (戴杰) <sup>1</sup>, Ji Zhou (周济)<sup>1,2*</sup>

The main files are as follows:

(1) OFHB dataset.zip - The Wheat Fusarium Head Blight spike classfication (OFHB) data.

(2) Model_save - YOLOv8-WFD model and Hierarchical clustering model

(3) Result - Resistance evaluation result (Batch processing). 

(4) Supplementary tables - Supporting materials for wheat FHB resistance evaluation platform

(5) ultralytics - Scripts required for the YOLOv8-WFD model to run

(4) Processing.ipynb - Python-based source coce that contains the pre-processing(Red tags extracted).

(5) FHB_traits_output.ipynb - Python-based source coce that contains the FHB traits output at different scales in wheat.

(6) Evaluatiob_platform.ipynb - Python-based source coce that contains the model integration and execution.

To install Python, Anaconda and Libraries
If you wish to run from the source code provided in this project, you will need to set up Python on your system.

• Read the beginner’s guide to Python if you are new to the language: https://wiki.python.org/moin/BeginnersGuide

• For Windows users, Python 3 release can be downloaded via: https://www.python.org/downloads/windows/

• To install Anaconda Python distribution:

1) Read the install instruction using the URL: https://docs.continuum.io/anaconda/install

2) For Windows users, a detailed step-by-step installation guide can be found via: https://docs.continuum.io/anaconda/install/windows

3) An Anaconda Graphical installer can be found via: https://www.continuum.io/downloads

4) We recommend users install the latest Anaconda Python distribution


Some dependencies of the Jupyter notebooks

Scikit-image =0.21; ultralytics =8.1.24; Pandas=2.0; Numpy=1.24.2; Scipy=1.9.1; joblib=1.3.2; OpenCV=4.8.1
