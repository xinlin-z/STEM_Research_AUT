# STEM_Research_AUT
Couresework of my STEM Research course at AUT 2025 semester one.

This was actually an image classificiation task which leveraged pre-trained VGG16 model and adapted it to binary classification scenario. The last two VGG blocks were set to trainable and a few data augmentation techniques were employed. I trained and evaluated everything on kaggle, where I can get a free GPU. 

More words about the code: 

* PyTorch was used.
* training.ipynb: main training code. The index variable for image files was pre-generated to speed up. Caching all original images data in CPU memory to wave disk IO. Support saving checkpoints automatically to disk and resume training process at any checkpoint later on.
* evaluation.ipybn: evaluation code. Load model and evaluate on two test dataset. Calculate AP, best possible F1-Score and draw PR-curve.



