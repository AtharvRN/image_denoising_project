# image_denoising_project
EE6310  Course Project (Image and Video Processing) supervised by [Prof. Sumohana S. Channappayya](https://people.iith.ac.in/sumohana/) </br>
As a part of this project, we investigated various techniques for Image Denoising and implemented the same. Some of the implementations are from scratch and some are based on other implementations. All details are mentioned in this [Report](https://github.com/AtharvRN/image_denoising_project/blob/main/Final_Project_Report_Team10.pdf) </br>
We divided the techniques into two major groups as follows:
- Classical Methods
  - Weiner Filtering
  - Bilateral Filtering
  - Wavelet Based Denoising
  - Total Variational Denoising
  - PCA Based
  - Non Local Means
  - BM3D
  - WNNM
- Deep Learning Based Methods
  - Autoencoder Based
  - DnCNN
  - RIDNet
  - CBDNet
  - PRIDNet

A comprehensive comparison of these methods was carried out based on their PSNR and SSIM performance. The code used for that can be found in the performance_metric directory. </br>
The CBSD68 dataset was used for testing and BSD400 was used for training the deep learning models. See [Report](https://github.com/AtharvRN/image_denoising_project/blob/main/Final_Project_Report_Team10.pdf) for more details.

Collaborators
- Atharv Ramesh Nair
- Nitish S
- V Rahul
- Saumyaranjan Mohanty
