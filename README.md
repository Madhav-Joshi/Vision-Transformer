# Vision-Transformer
Trained vision transformer for small dataset like CIFAR10 and CIFAR100 using TensorFlow.  
Sr.No. |   Names       |  Roll No.
 1)    | Tejas Shintre | 190010068
 2)    | Madhav Joshi  | 190110034
 3)    |  Shiv Modi    | 19D100011
 4)    | Aryan Jani    | 19D100002

Paper Title: Vision Transformer for Small-Size Datasets 
Authors: Seung Hoon Lee, Seunghyun Lee, Byung Cheol Song
Conference paper: CVPR 2021

We have implemented this paper with add-on modules Shifted Patch Tokenization (SPT) and Locality Self-Attention (LSA). The hyperparameters are changed to reduce training time and also it improved accuracy.

Run the 1st cell in any file to mount the drive if you want to save the trained model later in the code.

There are 2 files for CIFAR-10 datasets, one for learning rate 0.003 (vit_small3_cifar10.ipynb) and one for 0.001 (vit_small1_cifar10.ipynb). For CIFAR-100 dataset there is only one file with learning rate 0.001 (vit_small1_cifar100.ipynb).

We got Top 1 - Top 5 accuracy in ViT and SL-ViT after the model was trained. Atlast, we saved the model and load it back tested on test dataset and calculated Top 1 accuracy.

Code is replicated from https://keras.io/examples/vision/vit_small_ds/
