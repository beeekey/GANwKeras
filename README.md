# Vanilla GAN in Keras

<img src="etc/adam.gif">

This is an implementation of the basic GAN algorithm using Keras based on the original GAN paper by Ian Goodfellow et al.
Paper link: https://arxiv.org/abs/1406.2661

Find the Medium post explaining the use of the code here: 

I have uploaded the dataset used in the code to my Floydhub for easy downloading. Find it here: https://www.floydhub.com/mirantha/datasets/celeba

### Instruction to sun the sript

Download the dataset from the provided link and save the images to a folder named 'data_face' in the same directory as the script

Create another foler in the same directory named 'output_images' to store the generated images

Run the script


### Notes to run from beeekey

* create folder with input data in top directory and edit it in line 134
* create folder "output_images" to save newly created images
* added defined image size of class to train method --> defining size of input and output images once in the main class
