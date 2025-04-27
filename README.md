# STEM_Research_AUT
Couresework of my STEM Research course at AUT

I trained and evaluated everything on kaggle, where I can have a free GPU. So, all codes are in notebook format, enjoy...

* training.ipynb: main training code. Index for image files was pre-generated to speed up. Caching all original images data in CPU memory to wave disk IO. Support save checkpoints (latest N checkpoints) to disk and resume training process at any checkpoint later on.
* evaluation.ipybn: evaluation code. Load model and evaluate on two test dataset. Calculate AP, best possible F1-Score and draw PR-curve.



