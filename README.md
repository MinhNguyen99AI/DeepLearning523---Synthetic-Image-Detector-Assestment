# CS 523: Deep Learning (Spring 22)
## Methods to Detect GAN-Generated Images
---Synthetic-Image-Detector-Assestment
Deep Learning Boston University Final Project - Synthetic GAN images detector re-implementation and assestment. 

Project Report (Google Doc):- https://docs.google.com/document/d/1lbNA2VCtUeTrxGibGD4hsfwPq4agTxhlyJ1wTPBjESU/edit

Presentation (Google Slides):- https://docs.google.com/presentation/d/1krUXYfpzmqlbyrfA53yYeDE4Wx6tsYp40nwFmgY7wd0/edit?usp=sharing

Update Report (Google Doc):- https://docs.google.com/document/d/1HN4BIBhxD3Ur_bqPWqPzG2wsfgmeo6FvT3n39GCYtac/edit?usp=sharing

## Dataset

[Training Dataset](https://drive.google.com/file/d/1iVNBV0glknyTYGA9bCxT_d0CVTOgGcKh/view)

[Testing Dataset](https://drive.google.com/file/d/1z_fD3UKgWQyOTZIBbYSaQ-hz4AzUrLC1/view)

Directory should like this:-
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
|-- M-Gb  
|-- SRNet  
|-- Wang_2020_Files  
|-- Xception  
|-- ourOwnGan  
|-- ourOwnGan_Copy  
|-- patchForensic  
|-- patchForensic_nzotalis  
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
`-- spec  
```

## Reference Papers

[Main Reference Paper](https://arxiv.org/pdf/2104.02617.pdf)

Add other papers.

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
'''
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
'''
