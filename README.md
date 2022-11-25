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

Run the 1st cell to mount the drive if you want to save the trained model later in the code.

There are 2 files in each CIFAR-10 and CIFAR-100 Folders. One file has learning rate 0.001 and other has 0.003. The files which have 0.003 learning rate are having bad accuracy. They took almost same amount of time.

We got Top 1 - Top 5 accuracy in ViT and SL-ViT after the model was trained. Atlast, we saved the model and load it back tested on test dataset and calculated Top 1 accuracy.
