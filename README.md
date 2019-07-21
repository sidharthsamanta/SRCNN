# SRCNN
Modified Faster RCNN for Remote Sensing Imagery (Spatial Resolution Independent)

# Prerequisites 
1. Python 3
2. Anaconda Navigator
3. Minimum i5 processor with 8GB RAM
4. GPU (NVIDIA Preferred)

# Python Libraries
1. Create a new anaconda environment (in command prompt)
  ```
  C:\> conda create -n tensorflow1 pip python=3.5
  ```
2. Activate the enviromnet and update
  ```
  C:\> activate tensorflow1
  (tensorflow1) C:\>python -m pip install --upgrade pip
  ```
3. Install tensorflow-GPU
  ``` (tensorflow1) C:\> pip install --ignore-installed --upgrade tensorflow-gpu ```
4. Install following tools and Packages
  ```
  (tensorflow1) C:\> conda install -c anaconda protobuf
  (tensorflow1) C:\> pip install pillow
  (tensorflow1) C:\> pip install lxml
  (tensorflow1) C:\> pip install Cython
  (tensorflow1) C:\> pip install contextlib2
  (tensorflow1) C:\> pip install jupyter
  (tensorflow1) C:\> pip install matplotlib
  (tensorflow1) C:\> pip install pandas
  (tensorflow1) C:\> pip install opencv-python
  ```
# Instructions
1. Clone or download the repository. 
2. Download the inference graph from https://drive.google.com/open?id=13_kBwvTKLzY6HODNXM2IPcOd1ol47v2K and store it in a new subfolder named "inference_graph" in the srcnn folder.
3. Dpen the working directory (SRCNN) in command prompt and open jupyter notebook.
  ```
  C:\SRCNN> activate tensorflow1
  (tensorflow1) C:\SRCNN>jupyter notebook
  ```
4. Open the SRCNN.ipynb
5. Set the image path, spatial resolution value and overlapping percentange in relivant field.
6. Run all cell


Done

