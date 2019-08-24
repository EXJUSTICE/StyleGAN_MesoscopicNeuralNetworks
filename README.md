# Mesoscopic Neural Networks for Synthetic Image Identification
Inception-powered Synthetic Image Detection based on Mesoscopic Neural Network Approach. Based on Afchar's apublication  "MesoNet: a Compact Facial Video Forgery Detection Network".

Detailed tutorial, "Seeing is Believing — Mesoscopic Neural Networks for Synthetic Image Detection", available on [GradientCrescent](https://medium.com/gradientcrescent/seeing-is-believing-in-the-age-of-ai-mesoscopic-neural-networks-for-synthetic-image-detection-an-71bf2f08adb9).

## Structure
The are twoIpython Notebooks in this repository, covering the Meso4 and Meso4-Inception architectures, as well as the InceptionV3 architectures. These two notebooks are completely independent. Note that the InceptionV3 model has been commented out in both books - to run a benchmark, uncomment these and comment out the mesoscopic architecture instead.

## Dataset

500 images of FFHQ and StyleGAN datasets, representing true and synthetic data classes, respectively, were used to evaluate our models. Data is temporarily stored on a Google Drive, but is also available on the NVIDIA StyleGAN repository

