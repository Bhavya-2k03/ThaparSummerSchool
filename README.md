# Image Caption Generator
![image](https://user-images.githubusercontent.com/100507234/235939011-15956fdd-3e41-4740-88bf-9485ccab95f6.png)



## Use cases
* Some detailed usecases would be like an visually impaired person taking a picture from his phone and then the caption generator will turn the caption to speech for him to understand. 
* Advertising industry trying the generate captions automatically without the need to make them seperately during production and sales.
* Doctors can use this technology to find tumors or some defects in the images or used by people for understanding geospatial images where they can find out more details about the terrain.

![image](https://user-images.githubusercontent.com/100507234/235934594-48707694-74a0-489d-87e8-6d3adfb8d862.png)

<br>

## Dataset:
[FLICKR_8K](https://forms.illinois.edu/sec/1713398).
This dataset includes around 1500 images along with 5 different captions written by different people for each image. The images are all contained together while caption text file has captions along with the image number appended to it. The zip file is approximately over 1 GB in size.

![image](https://user-images.githubusercontent.com/100507234/235935000-79099ffe-9dee-45be-acfa-9a08f63c97d8.png)
<br>

## Flow of the project
#### a. Cleaning captions
#### b. Extracting features from images using VGG-16
#### c. Building LSTM model
#### d. Inferencing on test data

<br>
