# Nighttime Vehicle Detection Dataset
A dataset for vehicle classification in darkness collected and labeled in the Autonomous Robots Lab at the University of Nevada, Reno.

By Jack Currie, Brenda Penn, and Dusty Barnes

## 1. Ground Truth

The data in **gt10913.txt** is organized as follows, with single spaces delimiting each of the values on a line. The n-th row in the gt10913.txt file corresponds to the n-th image in the data directory, and is indicated by the "Image Number" field in each row.

The "x" and the "y" are the x-y coordinates of the top left corner of the vehicle with relation to the top left corner of the image.  

Image Num | Num Vehicles |  [x1   y1  width  height] for each vehicle
-------------------------------------------------------------------------------------
0           4               [139   248   163   80  ]  [272 230 132 49] [382 219 66 36] [425 208 49 39]



## 2.Images 

This dataset contains **10913** gray-scale images of night-time images of roads labeled img_0.jpg --> img_10913.jpg. The images all have dimensions of *1280 x 1024* pixels (width x height). Not all images in the dataset contain vehicles, though the majority (~90%) do. The data was collected using a PointGrey Chameleon 3 Grayscale camera (CM3-U3-13S2C-CS-BD).
 
Some images were collected from a **moving bus**, and others were collected with **roadside cameras** (having static backgrounds).

Images         |  Overview                                                                                             | Background 
-----------------------------------------------------------------------------------------------------------------------------------
0 - 2006       | Filmed from Bus, non-static background                                                                | Dynamic

2007 - 8247    | Filmed from roadside at intersection of N. Virginia St. and College Dr. (3 different vantage points)  | Static

8248 - 10193   | Filmed from roadside at intersection of Sierra St. and College Ct. (2 different vantage points)       | Static

Indicative images are shown below:
![indicative image](https://preview.ibb.co/jtr9WJ/cars_night.png "Indicative Image")

## 3. Download the Dataset

You may download the complete dataset following this [link](https://www.cse.unr.edu/~kalexis/datasets/cars-night/Vehicles_NightTime.tar.gz) or simply clone this repository. 

## Additional notes:
Another similar nighttime dataset from Long-Chen from Sun Yat-sen University can be found following this [link](http://www.carlib.net/?page_id=35).

This dataset provides an additional ~6000 images which are all in color, and will certainly be of interest to you if you are investigating this dataset.

## Contact:
You can contact us for any question or remark:
* [Jack Curie](mailto:jackcurrie@protonmail.com)
* [Kostas Alexis](mailto:kalexis@unr.edu)

## Acknowledgement

This material is based upon work related to the Intelligent Mobility project supported by the Governor's Office of Economic Development.

