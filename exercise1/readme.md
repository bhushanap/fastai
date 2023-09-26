# fastai
This is an implementation of the fastai exercise 1 for classification based on ResNet34
The resnet model has been finetuned against a custom dataset of landscape categories. Images were collected from google maps and manually labelled.

A sliding tile then moves across the test image and classifies each smaller region into one of the landscapes.
This helps generate segmentation grids like this.

Note: Will take a long time to run for larger images as that many forward passes need to be made in the model.

Here are some results:
<table>
  <tr>
    <td><img src="https://github.com/bhushanap/fastai/raw/main/exercise1/landscapes/grid_1.png" alt="grid 1" height="300"></td>
    <td><img src="https://github.com/bhushanap/fastai/raw/main/exercise1/landscapes/grid_2.png" alt="grid 2" height="300"></td>
    <td><img src="https://github.com/bhushanap/fastai/raw/main/exercise1/landscapes/grid_3.png" alt="grid 3" height="300"></td>
  </tr>
</table>

