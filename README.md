# HybridBrainTumor_Classification (Updated)
First, the project uses a neural network model to classify the brain MRI images into these four categories :
- Glioma
- Pituitary
- Meningioma
- No Tumor

Then I started working on the No Tumor dataset to see whether certain rare tumor cases were erringly classified as having no tumor. I used a Generative Adversarial Network (GAN) model to augment more images to mitigate bias as much as possible and then checked those images for certain characteristics that might signal the presence of a rare case of tumor. In the end, a binary classification model (here CNN) was trained with the help of a labeled dataset ( No Tumor / Rare Case ) and then tested on an unseen chunk of the same dataset. 

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
