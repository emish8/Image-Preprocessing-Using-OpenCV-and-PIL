# Image-Preprocessing-Using-OpenCV-and-PIL

## File 1

 1. Gray Coversion (avg method, cv2 filter , wieghted avg method)
 
![image](https://user-images.githubusercontent.com/83595196/204131296-f06adfeb-3e0c-4222-a53f-4c8f06531a10.png)

 2. Morhology (erosion, dilation, opening, closing, gradient, tophat, blackhat)
 
 ![image](https://user-images.githubusercontent.com/83595196/204131319-3c20e87b-d024-497c-b050-7847a89a76f0.png)

 3. Gray to Binary
 
![image](https://user-images.githubusercontent.com/83595196/204131351-a70eab61-63a0-4968-839a-ce5d77071550.png)


## File 2

1. Smoothing ( gausian, avg, w_avg, median, py_gaus, py_part_blur)
- OpenCV2: Gaussing BLur, Median Blur, Average Blur, Wieghted Average (filter2D)

- PIL: Gaussing Blur, Blur part of img
 ![image](https://user-images.githubusercontent.com/83595196/204131393-c6de704c-89e4-4948-a08c-77c65fd9fe44.png)

 
2. Filter ( min, max)
PIL - Min Filter ( image Darkening)
![image](https://user-images.githubusercontent.com/83595196/204131418-5b3d3dfe-29a2-4ac1-8f49-b80da3a47a52.png)



PIL - Max Fliter ( Image Brightening)
![image](https://user-images.githubusercontent.com/83595196/204131438-78dbf558-2eca-4186-b351-0a2e80fc67a7.png)



3. Noise Reduction
OpenCV2 -  Bilateral Filter
![image](https://user-images.githubusercontent.com/83595196/204131450-e40da229-416a-4a43-9b73-22b5387ef935.png)

OpenCV2  - Gaussing Blur
![image](https://user-images.githubusercontent.com/83595196/204131461-f75f5601-74d7-47e2-9f4d-c957089f96b2.png)



## File 3

Sobel - Vertical and Horizontal Feature Extraction
![image](https://user-images.githubusercontent.com/83595196/204131783-45176e62-0c6d-44c6-a6a6-f0f677a3e78a.png)

Laplace - Finding Edges
![image](https://user-images.githubusercontent.com/83595196/204131484-2b10d4f0-1e56-4ba4-a520-306a95cfb06e.png)

Unsharp masking - thourght subtration and PIL inbuilt function
![image](https://user-images.githubusercontent.com/83595196/204131489-3bcafa8f-27ba-4fd1-a376-41aee8a99521.png)
