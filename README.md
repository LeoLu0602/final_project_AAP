# Load data
(use NT15dataset_x_train.npy as an example)

import numpy as np

NT15_x_train = np.load('NT15dataset_x_train.npy')

# x_train / x_test
(use NT15_x_train as an example)

len(NT15_x_train[i]) = 20 + 20 x 20 + 20 x 20 x 20 + (20 + 10) + (20 + 10) = 20 + 400 + 8000 + 30 + 30 = 8480

NT15_x_train[i][:20]: AAC

NT15_x_train[i][20:420]: DPC

NT15_x_train[i][420:8420]: TC

NT15_x_train[i][8420:8450]: PseAAC

NT15_x_train[i][8450:]: PseAAC with a different correlation function


top 50, 100, 150, ... , 400

n_estimators: 20, 40, 80, 160
