# Image Compression - Group 2 (Out_of_Bounds)

## Team Members:
- **Priya Jani:** AU2040004  
- **Priyanshu Pathak:** AU2040241
- **Yansi Memdani:** AU2040028

**YouTube Link:** [Watch the Project Presentation](https://youtu.be/Irg2tuGJ4Fg)

## Abstract
The growing need for digital information storage and transmission necessitates efficient methods for compressing images and videos. This project explores Singular Value Decomposition (SVD), a technique that preserves image quality while compressing data. SVD utilizes a series of linear approximations through matrix transformations, retaining essential features and reducing storage requirements. This method focuses on eigenvalues, image rank, and compression ratios to achieve optimal results.

## Keywords
Singular Value Decomposition, linear matrix transformation, linear approximations, eigenvalues, rank, compression ratio.

## Results

1. **Impact of K on Compression:**
   - A smaller value of K results in higher compression, reducing the number of singular values in the matrix. This loss of data requires less storage space, leading to a higher compression ratio.
   - **Compression Ratio Formula:** Cr = m * n / (k * (m + n + 1))

2. **Quality Evaluation (MSE):**
   - Mean Squared Error (MSE) measures the quality of the compressed image concerning the original matrix. A lower MSE indicates better image quality, especially when K approaches the matrix's rank.

3. **Grayscale Compression:**
   - The MATLAB Grayscale approach demonstrates the significant role of K in compression, showcasing the drastic changes that occur with different K values.
   
   ![Grayscale Images](https://user-images.githubusercontent.com/76212148/143485433-68a17305-b293-4381-910a-250f08db80ad.png)
   - **Using 1, 2, 4, 8 singular values**

   ![Grayscale Images](https://user-images.githubusercontent.com/76212148/143485465-5e116555-6f0e-4bba-a6aa-95c93287b2bf.png)
   - **Using 16, 18, 50, 100 singular values**

4. **Color Image Compression:**
   - Colored images are divided into three layers, each compressed individually and then merged together. Compression alters colors as shown below.
   
   ![Layered Color Images](https://user-images.githubusercontent.com/76212148/143485534-b5d7aae7-754f-4e33-9af5-275330a09d17.png)
   ![Layered Color Images](https://user-images.githubusercontent.com/76212148/143485542-fb1c88cb-8a63-4941-95de-6c596cad4ba9.png)

5. **Error vs. Number of Singular Values (Colored Images):**
   - The relationship between error rate and the number of singular values taken for colored images follows a similar curve observed in grayscale compression.
     
   ![Error vs. Singular Values](https://user-images.githubusercontent.com/76212148/143485555-fea2b3b6-fb5e-4c67-a468-776d8bbba87d.png)

## References

- [1] Jameela, Rehna. (2011). "JPEG Image Compression using Singular Value Decomposition." IOSR Journal of Electrical and Electronics Engineering. 1. 81 - 88.
- [2] Kahu, S. and Rahate, R., 2013. "Image Compression using Singular Value Decomposition." [SciResPub](http://www.ijoart.org/docs/Image-Compression-using-Singular-Value-Decomposition.pdf), pp. 244-248.
- [3] "Singular value decomposition applied to digital image..." (n.d.). [Read More](https://sites.math.washington.edu/~morrow/498_13/svdphoto.pdf).
- [4] "Image compression using singular value..." - math. (n.d.). [Learn More](https://www.math.utah.edu/~goller/F15_M2270/BradyMathews_SVDImage.pdf).
