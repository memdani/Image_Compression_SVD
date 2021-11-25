# Image_Compression
**Group: 2 - Out_of_Bounds**

Priya Jani       --> AU2040004  

Priyanshu Pathak --> AU2040241

Yansi Memdani    --> AU2040028

_**Abstract**_—The increasing usage of digital information also requires storage and transmission of images and videos. A technique called SVD (Singular Value Decomposition) is used to compress these images without affecting the quality of the image. This linear matrix transformation uses a product of three matrices and compresses the image by keeping necessary features. It finds the basic structure of the image by transformation into a series of linear approximations. The main idea behind this is to select some eigenvalues to compress and reconstruct the image. It deals with the rank of image and compression ratio.

_**Keywords**_— Singular Value Decomposition, linear matrix transformation, linear approximations, eigenvalues, rank, compression ratio.

_**Results**_—

**1.** Smaller the K is, larger the compression. Less singular values
are present in matrix. As much of the data is lost and thus
less storage will be required to store the image.
Cr = m*n/ (k (m + n + 1))
Compression ratio will be high.

**2.** MSE is the error that determines quality. As K becomes
closer to the rank of matrix, better quality it would be as
compared to the original matrix. The matrix that is
reconstructed is approximately the same as MSE is small.

**3.** The MATLAB Grayscale approach showed that the k has
an important role in compression. The following images
show how drastic change can occur if we alter the value of
“k”.

![image](https://user-images.githubusercontent.com/76212148/143485433-68a17305-b293-4381-910a-250f08db80ad.png)

**Image outputs using 1,2,4,8 singular values**


![image](https://user-images.githubusercontent.com/76212148/143485465-5e116555-6f0e-4bba-a6aa-95c93287b2bf.png)

**Image outputs using 16,18,50,100 singular values**


**4.** The relation between error rate and number of singular
values taken is shown below. It is clearly observed that the
more singular values taken will relate more closely to the
original matrix and hence error rate is less and vice versa.

![image](https://user-images.githubusercontent.com/76212148/143485497-87fb1a32-c772-4570-9671-91fb85c39f1c.png)

**5.** The Colored Images are divided into 3 layers and each
layer is compressed individually and then merged together
as one. Compression does change the color and below is
shown the same.

![image](https://user-images.githubusercontent.com/76212148/143485534-b5d7aae7-754f-4e33-9af5-275330a09d17.png)

![image](https://user-images.githubusercontent.com/76212148/143485542-fb1c88cb-8a63-4941-95de-6c596cad4ba9.png)

**6.** The error and number of singular values taken for colored
images has same relation as grayscale. It shows same curve.

![image](https://user-images.githubusercontent.com/76212148/143485555-fea2b3b6-fb5e-4c67-a468-776d8bbba87d.png)

_**Refernces**_—

[1]	Jameela, Rehna. (2011). JPEG Image Compression using Singular Value Decomposition. IOSR Journal of Electrical and Electronics Engineering. 1. 81 - 88.

[2]	Kahu, S. and Rahate, R., 2013. Image Compression using Singular ValueDecomposition. [ebook] SciResPub., pp.244-248. Available at: <http://www.ijoart.org/docs/Image-Compression-using-Singular-Value-Decomposition.pdf> [Accessed 28 September 2021].

[3]	Singular value decomposition applied to digital image ... (n.d.). Retrieved October 20, 2021, from https://sites.math.washington.edu/~morrow/498_13/svdphoto.pdf.

[4]	Image compression using singular value ... - math. (n.d.). Retrieved October 20, 2021, from
https://www.math.utah.edu/~goller/F15_M2270/BradyMathews_SVDImage.pdf.
