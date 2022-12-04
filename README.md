# MDOLC-Multi-Dialect-Odia-Song-Lyric-Corpus-
Overview
The repository contains the code/data of the released Multi Dialect Odia Song Lyric Corpus (MDOLC). The data is already split into train/dev/test sets for the experiment. We also provided 230 songs in XML format for research purposes as shown below.



Model
The Supervised Autoencoder (SAE) used for the dialect detection task.



The code is also available for detecting Odia and Sambalpuri dialect.

Dependency
Python 3.6

PyTorch (torch=1.0.1, torchtext=0.4.0, torchvision=0.4.0)

Utilities (Skopt, sklearn, numpy, Zipfile, Pandas, Pickel)

How to Run ?
The dialect detection code supports both CPU/GPU. For running in CPU/GPU mode, enable/disable the "is_gpu" flag to "True" or "False" inside the "lang_detect_odia_samabalpuri.py" file.

Usage: Execute the following command on the command line to run using CPU:

python lang_detect_odia_samabalpuri.py
Contributor
Shantipriya Parida
Alakananda Tripathy
Satya Ranjan Dash
Shashikanta Sahoo
Support/Contact
Please feel free to contact for any support or enhancement.

Citation
If you found our research helpful or influential please consider citing

@inproceedings{parida-etal-2022-mdolc, title = "MDOLC: Multi Dialect Odia Song Lyric Corpus", author = {Parida, Shantipriya and Tripathy, Alakananda and Dash, Satya Ranjan and Sahoo, Shashikanta}, booktitle = "Proceedings of the International Conference on Recent Advancements in Artificial Intelligence and Soft Computing - ICAISC-2022", month = nov, year = "2022", }
