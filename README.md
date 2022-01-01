This repository contains my solutions to homeworks from my Deep Learning course at HSE University. 
Each homework was about choosing and training a model **from scratch** for a specific task on a given dataset and using only given libraries (mostly pytorch). In addition, it was prohibited to use any source code apart from the one available at pytorch website.
Solutions were ran in yandex datasphere using one V100 GPU in some reasonable time (around 8 hours each).

Each homework folder contains python notebook and a report in russian, though it is not required to understand notebook content (for GAN homework report contains image comparisons).

I was solving 3 tasks: image classification to 200 classes via resnet34 (accuracy), machine translation from english to german via pytorch transformer (BLEU), image translation via pix2pix GAN (FID). Scores for the first two tasks were among the top in the class. For the third task, resulting images are comparable to those from the paper.
