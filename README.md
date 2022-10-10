# Traffic_Light_Classifier

1.    PyTorch based custom CNN classifier for [German Traffic Sign Recognition Benchmark (GTSRB)](https://benchmark.ini.rub.de/gtsrb_dataset.html)
2.    Transfer Learning with ResNet-18 architecture 
3.    Results comparision for custom vs ResNet-18 classifier
4.    Prediction available for custom/internet images

## Data
The [GTSRB benchmark](https://benchmark.ini.rub.de/gtsrb_dataset.html) can also be downloaded from [torchvision.datasets.GTSRB](https://pytorch.org/vision/stable/generated/torchvision.datasets.GTSRB.html#torchvision.datasets.GTSRB).

The dataset available on [torchvision.datasets.GTSRB](https://pytorch.org/vision/stable/generated/torchvision.datasets.GTSRB.html#torchvision.datasets.GTSRB) has a total of 39270 images associated to 43 different classes. 


## Requirements
Python version > = 3.6

PyTorch, Torchvision, matplotlib, Pandas, PIL.


## Results

Epochs = 50

lr = 0.01

|  | Custom network | ResNet-18 (finetuned) | ResNet-18 (frozen convnet) |
|---|--------|------------|---------------|
|Accuracy | 97.9% | 99.926% | 87.652%|
