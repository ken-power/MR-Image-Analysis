# Analysis of 3D Magnetic Resonance (MR) Images

The goal of this project is to process and analyze magnetic resonance (MR) images of the brain.

# About the Dataset
This dataset contains publicly available pairs of healthy, structural T1-weighted (`T1-w`) and T2-weighted (`T2-w`) MR brain images from the Hammersmith Hospital in London. MR scanners are flexible machines that can be programmed to collect different anatomical information, which is where these two types of images come from (although, there are several other types of images that can be collected). The information provided by each of these types of images is used by physicians to diagnose and treat patients more effectively; the complementary information helps physicians disambiguate tissue and abnormalities ([Reinhold, 2021](#references)).

Unlike more traditional images, structural MR images are actually 3D image volumes, i.e., 3D arrays of numbers. Structural MR images show the anatomy of a patient, as opposed to functional MR images, which highlight areas of blood flow. So the numbers in our images correspond to the intensity of the anatomy due to the type of MR image being collected.

# References
* Jacob Reinhold, 2021. _[3D Medical Image Analysis with PyTorch](https://www.manning.com/liveproject/3d-medical-image-analysis-with-pytorch)_. Manning Publications.
* Jacob Reinhold, 2019. [Deep Learning with Magnetic Resonance and Computed Tomography Images](https://towardsdatascience.com/deep-learning-with-magnetic-resonance-and-computed-tomography-images-e9f32273dcb5): An introduction to the data, preprocessing techniques and deep network design for medical images. towardsdatascience.
* Eli Stevens, Luca Antiga, and Thomas Viehmann, 2020. _Deep Learning with PyTorch_. Manning Publications. 
* Mohamed Elgendy, 2020. _Deep Learning for Vision Systems_. Manning Publications.
* Jakub Langr and Vladimir Bok, 2019. _GANs in Action_. Manning Publications.
* PyTorch. [PyTorch Documentation](https://pytorch.org/docs/stable/index.html).
* Imperial College London. [IXI Dataset](https://brain-development.org/ixi-dataset/).
