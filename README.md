# Load data
(use NT15dataset_x_train.npy as an example)

import numpy as np

NT15_x_train = np.load(NT15dataset_x_train.npy)

# x_train / x_test
(use NT15_x_train as an example)

len(NT15_x_train[i]) = 20 + 20 x 20 + 20 x 20 x 20 + (20 + 3) = 20 + 400 + 8000 + 23

NT15_x_train[i][:20]: AAC

NT15_x_train[i][20:420]: DPC

NT15_x_train[i][420:8420]: TC

NT15_x_train[i][8420:]: PseAAC (for now lambda is set to 3)
