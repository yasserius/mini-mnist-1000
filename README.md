# mini-mnist-1000

A small subset of 1000 images from MNIST, 100 images for each digits.

## Load the images

Download the file and then load it with pickle

```python
import pickle

with open('mini-mnist-1000.pickle', 'rb') as f:
    data = pickle.load(f)

images = data['images'] # a list of 1000 numpy image matrices
labels = data['labels'] # a list of 1000 integer labels
```
