# Face antispoofing using mobilenet_v2

If you want to read this notebook, please open it in [google colab](https://colab.research.google.com/notebooks/intro.ipynb#recent=true) (you can use hyperlinks on functions and classes there)  
You can also open it in [nbviewer](https://nbviewer.jupyter.org) if you have a intermittent GitHub jupyter notebooks error "Sorry, something went wrong. Reload?"

### The model mobilenet_v2 with some added linear layers in the end is used to the face antispoofing classification.

### The training data consist of 1223 real and 7076 spoof photos. [MTCNN](https://github.com/timesler/facenet-pytorch) is used to crop faces. MTCNN could not find faces on 4 real and 72 spoof photos, they were removed from the training.
