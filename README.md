# blurry-image-detection
using laplacian method for detecting blur in images
## Discription
> In this project, I’ll  compute the amount of blur in an image using OpenCV, Python, and the Laplacian operator. By the end of this post, you’ll be able to apply the variance of the Laplacian method to your own photos to detect the amount of blurring.
Hint : the details in this project is discussed compeletly in my `.pptx` file as `checking blur in image` so,if you want to get complete information about blur images,please see this file.
## MODEL
> run commands in `blur_detection.ipynb` file,such as below:
>  * 1. mounting your google drive basis on your path.
```
from google.colab import drive
import os
drive.mount('/content/drive/')
os.chdir('/content/drive/MyDrive/checking-blur')
!ls
```
> * 2. run following command for applying model :
```
!python detect_blur.py --images sharpimages
--images : path of your test images
```
## Result
> after running algorithm on 2 folder iamges as `blurimages` and `sharpimages`,you can see results as below,suppose that if the score of variance of laplacian be less than `100` the images will be supposed as a blury,see the examples below :

| result  | 
| ----------- |
| ![sample](https://user-images.githubusercontent.com/53394692/111544388-a432e400-8789-11eb-93ef-c661e54a8259.PNG) | 

## License
> [Blur detection with OpenCV](https://www.pyimagesearch.com/2015/09/07/blur-detection-with-opencv/) by Adrian Rosebrock
