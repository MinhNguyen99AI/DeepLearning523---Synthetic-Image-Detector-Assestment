# DeepLearning523---Synthetic-Image-Detector-Assestment
Deep Learning Boston University Final Project - Synthetic GAN images detector re-implementation and assestment. 

[Training Dataset](https://drive.google.com/file/d/1iVNBV0glknyTYGA9bCxT_d0CVTOgGcKh/view)

[Testing Dataset](https://drive.google.com/file/d/1z_fD3UKgWQyOTZIBbYSaQ-hz4AzUrLC1/view)

[Reference Paper](https://arxiv.org/pdf/2104.02617.pdf)

Implemented 4 models:-

[Xception](https://github.com/MinhNguyen99AI/DeepLearning523---Synthetic-Image-Detector-Assestment/blob/main/Xception.ipynb)
[Wang2020](https://github.com/MinhNguyen99AI/DeepLearning523---Synthetic-Image-Detector-Assestment/blob/main/Wang_2020.ipynb)
[Spec](https://github.com/MinhNguyen99AI/DeepLearning523---Synthetic-Image-Detector-Assestment/blob/main/spec.ipynb)
[PatchForensics](https://github.com/MinhNguyen99AI/DeepLearning523---Synthetic-Image-Detector-Assestment/blob/main/PatchForensic.ipynb)

Libaries imported to run [Get list from SCC]

Specifications needed:- GPU for all

Time to run each notebook:- A lot.

Steps on How to install and run: -
  1. Download and unzip dataset from the google link. The size of the dataset is 88 gb combined and we could not upload it to Github. 
  2. The structure of the directory should be:-

project
  CNN_synth_testset
    biggan
    crn
    cyclegan
    ...
  progan_train
    airplane
    bicycle
    bird
    ...
  Notebooks
