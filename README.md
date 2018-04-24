# Deep-Auto-Coloring

Automatic coloring and shading of manga-style lineart, using Tensorflow + cGANs

This Repositories is python 3 porting and TensorFlow Version Compatibility for old Version.

### Outline and Color Hints :

![](https://github.com/cryingmiso/Deep-Auto-Coloring/blob/master/git_img/web_before.png)

### Result - Color Hint base Coloring or Auto Coloring:

![](https://github.com/cryingmiso/Deep-Auto-Coloring/blob/master/git_img/web_after.png)

## Setup

### Requirements
    - python 3.5
    - numpy 1.14.0
    - Tensorflow-GPU 1.3.0
    - OpenCV

### Running it
1. make a folder called "results"
2. make a folder called "imgs"
3. Fill the "imgs" folder with your own .jpg images, or run "download_images.py" to download from Safebooru.
4. Run "python main.py train". I trained for ~20 epochs, taking about 16 hours on one GPU.
5. To sample, run "python main.py sample"
6. To start the server, run "python server.py". It will host on port 8000.



Code based off [this pix2pix implementation](https://github.com/yenchenlin/pix2pix-tensorflow).
