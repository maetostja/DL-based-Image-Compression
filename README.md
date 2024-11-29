# DL-based-Image-Compression

This repository presents a project on image compression using the Kodak dataset. Three different approaches were explored:

1. *PCA Approach*: Implementing image compression using Principal Component Analysis (PCA).
2. *Autoencoder*: Utilizing an autoencoder architecture for image compression.
3. *Vector Quantized Variational AutoEncoder (VQ-VAE)*: Employing VQ-VAE for image compression.

## Results

The VQ-VAE approach yielded the most promising results, achieving a compression factor as high as 3.73. The compressed images exhibited good quality with SSIM values ranging from 0.93 to 0.97 and PSNR values ranging from 30 to 37 dB across different images. Moreover, the size of the VQ-VAE model was approximately 4.54 kB, making it suitable for deployment in low-compute environments.

## Steps to Run

Follow these steps to run the image compression project:

1. *Dataset Link*: Download the dataset from [Kaggle](https://www.kaggle.com/datasets/sherylmehta/kodak-dataset).
   
2. *Download the Files*: Obtain the IPython notebook and the dataset. Ensure that the dataset directory in the code is correctly specified.

3. *Execution on Kaggle*:
   - If you are using Kaggle, add the dataset as an input directly and execute the code.

4. *Additional Image for PCA Approach*:
   - For the PCA approach, an additional image is provided in the zip folder. Make sure to include this image for PCA implementation.

5. *Execution for AE and VQ-VAE*:
   - Ensure that the dataset is available in the code environment and execute the code for both autoencoder (AE) and vector quantized variational autoencoder (VQ-VAE) approaches.



## Submission Details

- *Submitted by*: Somshuvra Basu (B21EE069) and Uppala Giridhar (B21EE072)
- *Group*: C10 ES 16

For detailed information, including code, results, plots, and analysis, refer to the attached Python notebook and report.
