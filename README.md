# COVID-19-Chest-Radiography
The coronavirus outbreak came to light on December 31, 2019 when China informed the WHO of a cluster of cases of pneumonia of an unknown cause in Wuhan City in Hubei Province. Subsequently the disease spread to more Provinces in China, and to the rest of the world. The WHO has now declared it a pandemic. The virus has been named SARS-CoV-2 and the disease is now called COVID-19.
It was found in early studies that patients present abnormalities in chest radiography images that are characteristic of those infected with COVID-19. We detect such features to classify the X-ray images as Normal , Pneumonia and Covid.

## Content :
1. [Requirements](#requirements) to install on your system
2. [generating COVID dataset](Data/README.md)
3. Steps for [creating,training and evaluation](Codes/train_eval_inference.md)
4. [Results](#results)
5. [Links to pretrained models](docs/models.md)

## Requirements

The main requirements are listed below:

* Tensorflow 1.15
* OpenCV 4.2.0
* Python 3.7
* Numpy
* Scikit-Learn
* Matplotlib
* Shutil
* Tqdm 4.45.0 
* Jupyter notebook

## Results

### Inception-V3:
![inception](images/inception_ConfusionMatrix.png)

<div class="tg-wrap"><table class="tg">
  <tr>
    <th class="tg-7btt" colspan="3">Sensitivity (%)</th>
  </tr>
  <tr>
    <td class="tg-7btt">Normal</td>
    <td class="tg-7btt">Pneumonia</td>
    <td class="tg-7btt">COVID-19</td>
  </tr>
  <tr>
    <td class="tg-c3ow">91.3</td>
    <td class="tg-c3ow">91.1</td>
    <td class="tg-c3ow">86</td>
  </tr>
</table></div>

### Resnet:
![resnet](images/resnet_ConfusionMatrix.png)


<div class="tg-wrap"><table class="tg">
  <tr>
    <th class="tg-7btt" colspan="3">Sensitivity (%)</th>
  </tr>
  <tr>
    <td class="tg-7btt">Normal</td>
    <td class="tg-7btt">Pneumonia</td>
    <td class="tg-7btt">COVID-19</td>
  </tr>
  <tr>
    <td class="tg-c3ow">98</td>
    <td class="tg-c3ow">83</td>
    <td class="tg-c3ow">73</td>
  </tr>
</table></div>
