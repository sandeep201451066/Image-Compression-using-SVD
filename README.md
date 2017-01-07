# Image-Compression-using-SVD
Image compression techniques reduce the storage space occupied by the image without any loss to image quality. Thus the image size can be reduced by selecting proper compression technique depending on the requirement of user or application. 


# Methodology Used in Image Compression 
Initially the image which has to be compressed is given as an input. This input image is stored as an array of integers. Required ‘r’ value should be specified. Compression is then achieved by performing Singular value decomposition (SVD) on RGB components of the input image. The resultant decomposed matrix is regenerated after approximating S matrix.  

# Flow Diagram
This is tell you.How algorithm works.
![screenshot 46](https://cloud.githubusercontent.com/assets/19153198/21739353/f0115956-d4be-11e6-9f3e-8712f53feab6.png)

#**Results**  
Above provided program is also working for different image formats such as JPEG, PNG, TIFF, BMP etc
### Original Image
![horse](https://cloud.githubusercontent.com/assets/19153198/21739397/03a3324a-d4c0-11e6-9a4a-72ca86e33e4a.jpg)
**Dimensions: - 1366 x 768 
Size: - 372 KB**
### Output Image for Different r values
![horse30](https://cloud.githubusercontent.com/assets/19153198/21739398/0f570c88-d4c0-11e6-8d3c-a00431580d77.jpg)
**r = 30
CR = 2.5
Size = 144KB**
![horse60](https://cloud.githubusercontent.com/assets/19153198/21739399/0f58a192-d4c0-11e6-86d8-31e0422108b8.jpg)
**r = 60
CR = 2.2
Size = 171KB**
![horse100](https://cloud.githubusercontent.com/assets/19153198/21739400/0f594ee4-d4c0-11e6-8b0d-3a8688da3874.jpg)
**r = 100
CR = 1.9
Size = 189KB**
![horse150](https://cloud.githubusercontent.com/assets/19153198/21739401/0f61838e-d4c0-11e6-81ab-393ef45ad346.jpg)
**r = 150
CR = 1.8
Size = 200KB**
