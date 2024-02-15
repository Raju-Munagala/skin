
# Skin detection




## 1. A brief report on the steps you followed.

- Input image RGB to YCbCr
- Crmax and Cbmin computation
- Image-wise computation of the correlation rules parameters
- Image-wise correlation rules check

## 2. Observations on Algorithm
 
![App Screenshot](https://github.com/123mpozzi/nbrancati-py/blob/main/docs/trapezia_params.png?raw=true)


## 3.Any challenges faced and how you addressed them.

 - Instead of training the model, this algorithm deals with color spaces. So we need to know about color spaces.
 - In this algorithm we are also dealing with "Histograms".so we need to know about the histograms.
 - Finally the major challenge I have faced and not at done with that challenges is "the skin related colors like red,brown,yellow are also detecting in place of skin"

<p float="left">
  <img src="https://github.com/Raju-Munagala/skin/blob/main/208T1A05F9.jpg" width="33%" />
  <img src="https://github.com/Raju-Munagala/skin/blob/main/d4104c73-d7b1-455d-922d-56c2e16df41c.png" width="33%" />
</p>


<p float="left">
  <img src="https://github.com/Raju-Munagala/skin/blob/main/manu_1.jpg" width="33%" />
  <img src="https://github.com/Raju-Munagala/skin/blob/main/5ab9ff17-68d7-4038-9ec4-f550b59b18b1.png" width="33%" />
</p>
