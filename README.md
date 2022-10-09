# CIFAR10 Image Classification

This is the image classification model for the CIFAR10 dataset. This is one of the most important and benchmark datasets when it comes to computer vision tasks. This model uses PyTorch to create a Model and train the model. 

# How to run the notebook?

It is quiet simple, if you are using `Anaconda` then what you want to do is create a new environment using:

```Bash
conda create -n new_env_name
```

After this activate your newly created by:

```Bash
conda activate new_env_name
```

After activating the environment, do this. this will install all dependencies that are require to run the notebook.

```Bash
pip install -r requirements.txt
```

You can now run the jupyter notebook and create the model.✔

# Some results from the training: 🏁
After training the model for 100 epochs, here are some results. Tradionally, simple CNN models haven't performed very well on the CIFAR10 dataset. To increase the accuracy, you need to make the model way more complex, which not increases the training time, but you also risk overfitting. A better alternative would be to use pre-trained models such as VGG or ResNet, they give way better performance and faster training times than traditional CNN models. 