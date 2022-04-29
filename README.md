
# SuperpixelGridMasks

<img alt="SuperpixelGridMasks data augmentation" src="SuperpixelGridMasks.png"></img>

# What is SuperpixelGridMasks?

SuperpixelGridMasks is a semantic data augmentation approach which permits to generate various complementary images from original sensor-based data of varied natures e.g. X-Ray scans,  vehicular scenes, people images (see data samples). This approach allows to increase the size of your image-based training datasets towards expecting better performances in your analysis tasks. Experiments have shown that the approach can be efficient for image classification tasks. This work is currently under review. Once reviewed, source codes and complementary results will be publicly made available online. 

For more details about this work:

`Update April 20, 2022:` 

> Karim Hammoudi, Adnane Cabani, Bouthaina Slika, Halim Benhabiles, Fadi Dornaika and Mahmoud Melkemi. SuperpixelGridCut, SuperpixelGridMean and SuperpixelGridMix Data Augmentation, arXiv:2204.08458, 2022. 
>  <a href=https://doi.org/10.48550/arxiv.2204.08458>https://doi.org/10.48550/arxiv.2204.08458</a>


# Augmentation examples


## Samples of augmented X-Ray scans <sup>(generated from the Kaggle dataset Chest X-ray Images (Pneumonia))</sub>

<p align="center">
<div align="center">
<b>X-ray scans (q=1000, r=0.4, with boundaries)</b></div> 
</p>

<table>
<tr>
<td><img alt="X-Ray" width="175px" align="center" src="examples/xray_image1.jpeg"/> <br><div align="center">Image 1</div> </td>
<td><img alt="X-Ray" width="175px" align="center" src="examples/xray_SuperpixelGridCut1000P04boundaries.jpeg"/><br><div align="center">SuperpixelGridCut</div></td>
  <td><img alt="X-Ray" width="175px" align="center" src="examples/xray_SuperpixelGridMean1000P04boundaries.jpeg"/><br><div align="center">SuperpixelGridMean</div></td>
  <td><img alt="X-Ray" width="175px" align="center" src="examples/xray_image2.jpeg"/><br><div align="center">Image 2</div></td>
  <td><img alt="X-Ray" width="175px" align="center" src="examples/xray_SuperpixelGridMix1000P04boundaries.jpeg"/><br><div align="center">SuperpixelGridMix</div></td>
</tr>
</table>

<p align="center">
<div align="center">
<b>X-ray scans (q=1000, r=0.4, without boundaries)</b></div> 
</p>

<table>
<tr>
<td><img alt="X-Ray" width="175px" align="center" src="examples/xray_image1.jpeg"/><br><div align="center">Image 1</div> </td>
<td><img alt="X-Ray" width="175px" align="center" src="examples/xray_SuperpixelGridCut1000P04.jpeg"/><br><div align="center">SuperpixelGridCut</div></td>
  <td><img alt="X-Ray" width="175px" align="center" src="examples/xray_SuperpixelGridMean1000P04.jpeg"/><br><div align="center">SuperpixelGridMean</div></td>
  <td><img alt="X-Ray" width="175px" align="center" src="examples/xray_image2.jpeg"/><br><div align="center">Image 2</div></td>
  <td><img alt="X-Ray" width="175px" align="center" src="examples/xray_SuperpixelGridMix1000P04.jpeg"/><br><div align="center">SuperpixelGridMix</div></td>
</tr>
</table>

## Samples of augmented people images <sup>(generated from a PASCAL VOC benchmark dataset)</sup>


<p align="center">
<div align="center">
<b>Pedestrian images (q=100, r=0.4, with boundaries)</b></div> 
</p>

<table>
<tr>
<td>
<img alt="Person" width="175px" align="center" src="examples/person_189.png"/><br>
<div align="center">Image 1</div>
</td>
<td>
<img alt="Person" width="175px" align="center" src="examples/SEG100P0.4M0_person_18_AB.png"/><br>
<div align="center">SuperpixelGridCut</div>
</td>
<td><img alt="Person" width="175px" align="center" src="examples/SEG100P0.4M1_person_18_AB.png"/><br>
<div align="center">SuperpixelGridMean</div>
</td>
<td><img alt="Person" width="175px" align="center" src="examples/person_187.png"/><br><div align="center">Image 2</div></td>
<td><img alt="Person" width="175px" align="center" src="examples/person_189_AB.png"/><br>
<div align="center">SuperpixelGridMix</div>
</td>
</tr>
</table>

<p align="center">
<div align="center">
<b>Pedestrian images (q=100, r=0.4, without boundaries)</b></div> 
</p>

<table>
<tr>
<td>
<img alt="Person" width="175px" align="center" src="examples/person_189.png"/><br>
<div align="center">Image 1</div>
</td>
<td>
<img alt="Person" width="175px" align="center" src="examples/SEG100P0.4M0_person_18_A.png"/><br>
<div align="center">SuperpixelGridCut</div>
</td>
<td><img alt="Person" width="175px" align="center" src="examples/SEG100P0.4M1_person_18_A.png"/><br>
<div align="center">SuperpixelGridMean</div>
</td>
<td><img alt="Person" width="175px" align="center" src="examples/person_187.png"/><br><div align="center">Image 2</div></td>
<td><img alt="Person" width="175px" align="center" src="examples/person_189_A.png"/><br>
<div align="center">SuperpixelGridMix</div>
</td>
</tr>
</table>

## Samples of augmented vehicular images <sup>(generated from a PASCAL VOC benchmark dataset)</sup>


<p align="center">
<div align="center">
<b>Vehicle images (q=200, r=0.4, with boundaries)</b></div> 
</p>

<table>
<tr>
<td><img alt="Car" width="175px" align="center" src="examples/car_image1.png"/> <br><div align="center">Image 1</div> </td>
<td><img alt="Car" width="175px" align="center" src="examples/car_SuperpixelGridCut200P04boundaries.jpeg"/><br><div align="center">SuperpixelGridCut</div></td>
  <td><img alt="Car" width="175px" align="center" src="examples/car_SuperpixelGridMean200P04boundaries.jpeg"/><br><div align="center">SuperpixelGridMean</div></td>
  <td><img alt="Car" width="175px" align="center" src="examples/car_image2.png"/><br><div align="center">Image 2</div></td>
  <td><img alt="Car" width="175px" align="center" src="examples/car_SuperpixelGridMix200P04boundaries.jpeg"/><br><div align="center">SuperpixelGridMix</div></td>
</tr>
</table>

<p align="center">
<div align="center">
<b>Vehicle images (q=200, r=0.4, without boundaries)</b></div> 
</p>

<table>
<tr>
<td><img alt="Car" width="175px" align="center" src="examples/car_image1.png"/><br><div align="center">Image 1</div> </td>
<td><img alt="Car" width="175px" align="center" src="examples/car_SuperpixelGridCut200P04.jpeg"/><br><div align="center">SuperpixelGridCut</div></td>
  <td><img alt="Car" width="175px" align="center" src="examples/car_SuperpixelGridMean200P04.jpeg"/><br><div align="center">SuperpixelGridMean</div></td>
  <td><img alt="Car" width="175px" align="center" src="examples/car_image2.png"/><br><div align="center">Image 2</div></td>
  <td><img alt="Car" width="175px" align="center" src="examples/car_SuperpixelGridMix200P04.jpeg"/><br><div align="center">SuperpixelGridMix</div></td>
</tr>
</table>

# Classification results

<div align="center">
  
| Augmentation              | Parameters      | Accuracy (%)       |
|---------------------------|-----------------|--------------------|
| Baseline                  |        -        |        57.81       |
| Horizontal flip           |        -        |        62.50       |
| Adjust brightness         |    delta=0.1    |        57.81       |
| CutOut                    |      r=0.2      |        65.63       |
| CutOut                    |      r=0.4      |        65.63       |
| SuperpixelGridCut (ours)  |  (q=100, r=0.2) |64.06 (+6.25)       |
| SuperpixelGridMean (ours) | (q=1000, r=0.4) | **75.00 (+17.19)** |
| CutMix                    |      r=0.2      |        67.19       |
| CutMix                    |      r=0.4      |        60.94       |
| SuperpixelGridMix (ours)  |  (q=100, r=0.2) | **75.00 (+17.19)** |
  
</div>
<div align="center">Classification results of our proposed data augmentation
methods <br> and diverse ones obtained by training from scratch VGG19 <br> with a PASCAL
VOC dataset and varied parametrization.
</div>
<br><br>
For more details and results, you can refer to the article: <a href=https://doi.org/10.48550/arxiv.2204.08458>https://doi.org/10.48550/arxiv.2204.08458</a>

# Team

<b>Project leaders: </b>

- Karim Hammoudi, Université de Haute-Alsace, IRIMAS, [karim.hammoudi@uha.fr](mailto:karim.hammoudi@uha.fr)

- Adnane Cabani, ESIGELEC/IRSEEM, [adnane.cabani@esigelec.fr](mailto:adnane.cabani@esigelec.fr)

Note: project leaders equally contributed to this work.

<b>Contributors: </b>

- Bouthaina Slika, University of the Basque Country, Spain, [bslika001@ikasle.ehu.eus](mailto:bslika001@ikasle.ehu.eus)

- Halim Benhabiles, Yncrea Hauts-de-France, IEMN Lille, [halim.benhabiles@yncrea.fr](mailto:halim.benhabiles@yncrea.fr)

- Fadi Dornaika, University of the Basque Country \& IKERBAQUE foundation, [fadi.dornaika@ehu.es](mailto:fadi.dornaika@ehu.es)

- Mahmoud Melkemi, Université de Haute-Alsace, IRIMAS, [mahmoud.melkemi@uha.fr](mailto:mahmoud.melkemi@uha.fr)


# Bibtex references

> Karim Hammoudi, Adnane Cabani, Bouthaina Slika, Halim Benhabiles, Fadi Dornaika and Mahmoud Melkemi. SuperpixelGridCut, SuperpixelGridMean and SuperpixelGridMix Data Augmentation, arXiv:2204.08458, 2022. 
>  <a href=https://doi.org/10.48550/arxiv.2204.08458>https://doi.org/10.48550/arxiv.2204.08458</a>

```
@misc{HammoudiCabaniSuperpixelGridMasks,
  doi = {10.48550/ARXIV.2204.08458},
  url = {https://arxiv.org/abs/2204.08458},
  author = {Hammoudi, Karim and Cabani, Adnane and Slika, Bouthaina and Benhabiles, Halim and Dornaika, Fadi and Melkemi, Mahmoud},
  keywords = {Computer Vision and Pattern Recognition (cs.CV), Artificial Intelligence (cs.AI), Information Retrieval (cs.IR), Machine Learning (cs.LG), FOS: Computer and information sciences, FOS: Computer and information sciences, I.4; I.2, 65D18, 94A08},
  title = {SuperpixelGridCut, SuperpixelGridMean and SuperpixelGridMix Data Augmentation},
  publisher = {arXiv},
  year = {2022},
  copyright = {Creative Commons Attribution Non Commercial No Derivatives 4.0 International}
}

