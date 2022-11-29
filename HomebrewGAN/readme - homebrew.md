# CMPE258_TEAM_PROJECT

Group Members -

- John Wang 015938845 john.wang@sjsu.edu MSAI
- Amy Phan 012194572 amylan-anh.phan@sjsu.edu MSSE
- Jack Zhu 012218128 jiali.zhu@sjsu.edu MSAI
- David Archer guosheng.zhang@sjsu.edu MSAI

## link for dataset:

https://www.kaggle.com/datasets/jessicali9530/celeba-dataset

## Requirement and Version

Highly suggest using device that has at least 8GB of GPU memory or more or use google colab Pro/+ for training

```
tensorflow ==2.8.0
numpy ==1.21.6
pandas==1.1.3
matplotlib==3.3.2
tqdm==4.50.2
Pillow==9.3.0
```

## 2 ways to run code

## 1 run on google colab (Recommended!)
1. upload homebrew_gans_final.ipynb to google colab
2. upload kaggle api key.json into file directory (step 1 of https://medium.com/unpackai/how-to-use-kaggle-datasets-in-google-colab-f9b2e4b5767c)
3. click run all

## 2 run locally
need nested local directory named 'img_align_celeba/img_align_celeba'
need local directory named 'results'
```
pip install pipenv==2022.1.8
pipenv shell
pip install -r requirement.txt
python homebrew_gans_final.py
```

### Notes
- completed images will be in 'results' folder
- should take 3-6 hours to run depending on GPU
- you can save models for generator, discriminator and GAN as .h5 but you only need generator.h5 to produce images
- code can generate with saved generator.h5
