# Medical Image Segmentation Using Computer Vision Algorithms

## Otsu and Multi-otsu thresholding
Used for separating contents of an image into foreground and background.  
![1](https://user-images.githubusercontent.com/31370694/168498036-9570e1b2-0e7e-4e80-8105-ad639ebf3c44.png)  

## Graph-cut
Used for separating contents of an image into foreground and background using a graph get the min-cut which produces optimal segmentation.  
![2](https://user-images.githubusercontent.com/31370694/168498058-807524ae-55b4-40b5-aed7-720bcec7a873.png)  

## Random Walker
Few pixels are labeled as seeds and a random walker is initiated from each of the other pixels. The probability for each random walker corresponding to arriving at each seed is calculated and the pixel is given the label with seed having highest probability  
![3](https://user-images.githubusercontent.com/31370694/168498100-5041df57-abf6-46bd-a254-281d8e85be8b.png)  
