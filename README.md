# Numpy-Task
Following code is to load an image using cv2 library. cv2 library loads the image as numpy array. Fill missing code to replace red pixels with black codes.



import cv2

import numpy as np

from PIL import Image

im_path = "abc.png"

im_array = cv2.imread(im_path)

display(Image.fromarray(cv2.cvtColor(im_array, cv2.COLOR_BGR2RGB)))

your code to replace

display(Image.fromarray(cv2.cvtColor(im_array, cv2.COLOR_BGR2RGB)))
