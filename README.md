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
|-- Co_Net_Main.ipynb
|-- Dataset_Creation_Path_to_Label.ipynb
|-- GPU_Check.ipynb
|-- M-Gb
|   |-- model9.pt
|   |-- paranoid_save.pt
|   |-- test_accs.txt
|   |-- test_loader.pt
|   |-- train_loader.pt
|   `-- valid_loader.pt
|-- M-Gb.ipynb
|-- PatchForensic.ipynb
|-- PathForensic_nzotalis.ipynb
|-- SRNet
|   |-- SRNet.ipynb
|   |-- SRNet.pt
|   |-- SRNet.txt
|   |-- SRNet_line.svg
|   |-- SRNet_training_vis.txt
|   `-- SRNet_valid_vis.txt
|-- Test_Dataset_Labels.csv
|-- Train_Dataset_Labels.csv
|-- Unzipping.ipynb
|-- Wang_2020.ipynb
|-- Wang_2020_Files
|   |-- co_net_model_trained.pt
|   `-- wang_2020_model_trained.pt
|-- Xception
|   |-- Xception.ipynb
|   |-- Xception.pt
|   |-- Xception.txt
|   |-- Xception_line.svg
|   |-- Xception_mis.pdf
|   |-- Xception_training_vis.txt
|   `-- Xception_valid_vis.txt
|-- fake.png
|-- fake_1.png
|-- fake_2.png
|-- fake_3.png
|-- fake_4.png
|-- fake_5.png
|-- ourOwnGan
|-- ourOwnGan-Copy.ipynb
|-- ourOwnGan-Copy1.ipynb
|-- ourOwnGan.ipynb
|-- ourOwnGan_Copy
|   |-- test_loader.pt
|   |-- train_loader.pt
|   `-- valid_loader.pt
|-- patchForensic
|   |-- test_loader.pt
|   |-- train_loader.pt
|   `-- valid_loader.pt
|-- patchForensic_nzotalis
|   |-- final_save.pt
|   |-- model0.pt
|   |-- model1.pt
|   |-- test_accs.txt
|   |-- test_loader.pt
|   |-- train_loader.pt
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
|-- real.png
|-- real_1.png
|-- real_2.png
|-- real_3.png
|-- real_4.png
|-- real_5.png
|-- spec
|   |-- paranoid_save.pt
|   |-- test_accs.txt
|   |-- test_loader.pt
|   |-- train_loader.pt
|   `-- valid_loader.pt
|-- spec.ipynb
|-- test.ipynb
`-- test.txt
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
