# CS 523: Deep Learning Project (Spring 22)
## Methods to Detect GAN-Generated Images 

Project Report (Github):- https://github.com/MinhNguyen99AI/DeepLearning523---Synthetic-Image-Detector-Assestment/blob/main/523%20Project%20Final%20Report.pdf

Presentation (Google Slides):- https://docs.google.com/presentation/d/1krUXYfpzmqlbyrfA53yYeDE4Wx6tsYp40nwFmgY7wd0/edit?usp=sharing

## (1) Dataset

Our dataset can be found here:

[Source of Datasets](https://github.com/PeterWang512/CNNDetection#3-dataset)

- [Training Dataset](https://drive.google.com/file/d/1iVNBV0glknyTYGA9bCxT_d0CVTOgGcKh/view)  
- [Testing Dataset](https://drive.google.com/file/d/1z_fD3UKgWQyOTZIBbYSaQ-hz4AzUrLC1/view)


## (2) Requirements

Python Version - python3/3.8.6 

Libaries required:- 
1. pytorch/1.7.0 
2. tensorflow/2.3.1 
3. transformers/4.5.0

Time to run each notebook:- 30 min to 1 hour per epoch, depending on model complexity.

## (3) Steps on How to install and run: -

  1. Download the datasets from the google link above. The size of the datasets is 88 gb combined and we could not upload it to Github.
  2. Unzip the two zip files (CNN_synth_testset.zip & progan_train.zip) using Dataset_Unzipping.ipynb notebook. Or using any inbuilt unzipping software. The structure of the directory after unzipping should look like this:-

```
.
|-- CNN_synth_testset
|   |-- biggan
|   |-- crn
|   |-- cyclegan
|   |-- deepfake
|   |-- gaugan
|   |-- imle
|   |-- progan
|   |-- san
|   |-- seeingdark
|   |-- stargan
|   |-- stylegan
|   |-- stylegan2
|   `-- whichfaceisreal
|-- Co_Net.ipynb
|-- Dataset_Unzipping.ipynb
|-- M-Gb
|   |-- model9.pt
|   `-- test_accs.txt
|-- M-Gb.ipynb
|-- PatchForensic.ipynb
|-- SRNet.ipynb
|-- Wang_2020.ipynb
|-- Xception.ipynb
|-- ourOwnGan.ipynb
|-- patchForensic_nzotalis
|   |-- final_save.pt
|   |-- test_accs.txt
|   `-- valid_loader.pt
|-- progan_train
|   |-- airplane
|   |-- bicycle
|   |-- bird
|   |-- boat
|   |-- bottle
|   |-- bus
|   |-- car
|   |-- cat
|   |-- chair
|   |-- cow
|   |-- diningtable
|   |-- dog
|   |-- horse
|   |-- motorbike
|   |-- person
|   |-- pottedplant
|   |-- sheep
|   |-- sofa
|   |-- train
|   `-- tvmonitor
|-- spec
|   |-- paranoid_save.pt
|   `-- test_accs.txt
`-- spec.ipynb
```
  3. Run the notebooks. Each notebook is named as their respective models. All the notebooks can run without any changes needed.

## (4) References

[Main Reference Paper](https://arxiv.org/abs/2104.02617)

References Papers for each models:-   
1. [Xception](https://ieeexplore.ieee.org/document/8397040)  
2. [Wang2020](https://arxiv.org/abs/1912.11035)  
3. [Spec](https://arxiv.org/abs/1907.06515)  
4. [PatchForensic](https://arxiv.org/abs/2008.10588)  
5. [Co-Net](https://arxiv.org/abs/1903.06836)  
6. [M-Gb](https://arxiv.org/abs/1902.11153)  
7. [SRNet](http://www.ws.binghamton.edu/fridrich/research/SRNet.pdf)  

Other references:-  
1. [Tutorial for Pytorch Dataloader](https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html)
2. [Xception model reference](https://github.com/tstandley/Xception-PyTorch)
3. [SR-Net model reference](https://github.com/brijeshiitg/Pytorch-implementation-of-SRNet)
4. [DCGAN Pytorch Tutorial](https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html)

## (5) Link to Implementations (within Repository):-

1. [Xception](https://github.com/MinhNguyen99AI/DeepLearning523---Synthetic-Image-Detector-Assestment/blob/main/Xception.ipynb)  
2. [Wang2020](https://github.com/MinhNguyen99AI/DeepLearning523---Synthetic-Image-Detector-Assestment/blob/main/Wang_2020.ipynb)  
3. [Spec](https://github.com/MinhNguyen99AI/DeepLearning523---Synthetic-Image-Detector-Assestment/blob/main/spec.ipynb)  
4. [PatchForensic](https://github.com/MinhNguyen99AI/DeepLearning523---Synthetic-Image-Detector-Assestment/blob/main/PatchForensic.ipynb)  
5. [Co-Net](https://github.com/MinhNguyen99AI/DeepLearning523---Synthetic-Image-Detector-Assestment/blob/main/Co_Net.ipynb)  
6. [M-Gb](https://github.com/MinhNguyen99AI/DeepLearning523---Synthetic-Image-Detector-Assestment/blob/main/M-Gb.ipynb)  
7. [SRNet](https://github.com/MinhNguyen99AI/DeepLearning523---Synthetic-Image-Detector-Assestment/blob/main/SRNet.ipynb)  
8. [Our own GAN](https://github.com/MinhNguyen99AI/DeepLearning523---Synthetic-Image-Detector-Assestment/blob/main/ourOwnGan.ipynb)  
