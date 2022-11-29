# Keras StyleGAN
## Code taken from: https://keras.io/examples/generative/stylegan/

### Dataset link
https://www.kaggle.com/datasets/jessicali9530/celeba-dataset

### Requirements
- Python

### How to train model
1. Create a python virtual environment and activate it (optional)
2. Install requirements
```
pip install -r requirements.txt
```
3. Train the model
```
python keras_stylegan_128.py <path to directory of dataset images>
```
4. After each epoch, the generated images will be displayed and the checkpoints will be saved in the checkpoints directory

Note: If you want better results, increase the 'steps_per_epoch' on line 703 in keras_stylegan_128.py