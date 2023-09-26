# fastai
This is an implementation of the fastai exercise 1 for classification based on ResNet34
The resnet model has been finetuned against a custom dataset of landscape categories. Images were collected from google maps and manually labelled.

A sliding tile then moves across the test image and classifies each smaller region into one of the landscapes.
This helps generate segmentation grids like this.

Note: Will take a long time to run for larger images as that many forward passes need to be made in the model.

Here are some results:
![grid_1](https://github.com/bhushanap/fastai/assets/83635464/d9ab9818-7f85-427f-be19-a9cdd3ab8b60)
![grid_2](https://github.com/bhushanap/fastai/assets/83635464/e23d736b-9be3-4c5b-ab9f-ef9e856794ae)
![grid_3](https://github.com/bhushanap/fastai/assets/83635464/9fb1fe8b-38eb-4792-876b-cf49d36baf50)
