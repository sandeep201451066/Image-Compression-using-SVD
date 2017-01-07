# Image-Compression-using-SVD
Image compression techniques reduce the storage space occupied by the image without any loss to image quality. Thus the image size can be reduced by selecting proper compression technique depending on the requirement of user or application. 


# Methodology Used in Image Compression 
Initially the image which has to be compressed is given as an input. This input image is stored as an array of integers. Required ‘r’ value should be specified. Compression is then achieved by performing Singular value decomposition (SVD) on RGB components of the input image. The resultant decomposed matrix is regenerated after approximating S matrix.  
