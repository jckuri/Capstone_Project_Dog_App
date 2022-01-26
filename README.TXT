PREREQUISITES:

This project has the following imports:

import torch
import cv2
import os
import requests
import zipfile
import numpy as np
from glob import glob
import matplotlib.pyplot as plt                        
import torchvision.models as models
from PIL import Image
import torchvision.transforms as transforms
from torch.autograd import Variable
import torchvision 
import torch.nn as nn
import torch.nn.functional as F
import torch.optim as optim

Please make sure that all these Python modules are correctly installed
and working well. Otherwise you won't be able to execute the project.
Moreover, Python 3 needs to be correctly installed in your computer.

TESTING THE DOG APP WITH OTHER IMAGES:

Testing the Dog App with other images just requires that you store
other images inside the directory 'images2'.

And then you will add the filenames of images to this list of images.
This code is executed at the end of the Jupyter notebook "dog_app.ipynb"

--------------------------------------------------------------------------------

images = ['jckuri1.jpg', 'jckuri2.jpg', 'jckuri3.jpg', 'jckuri4.jpg', 'Negrita.jpg', 'Negrita2.jpg', 'saint-bernard.jpeg', 'white-bulldog.jpg', 'Siberian-husky.jpg']

for image in images:
    run_app(image)
    
--------------------------------------------------------------------------------
