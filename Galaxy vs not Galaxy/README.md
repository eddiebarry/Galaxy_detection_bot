# Quick Start - Galaxy vs Not Galaxy #


HOW TO RETRAIN
==============


### Download Datasets ###
1. Download the cifar_10 [image dataset](https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz)
2. Download GalaxyZoo galaxy [dataset](https://www.kaggle.com/c/3175/download-all)


### Transfer images to data folder ###
1. Unzip both the files
2. Transfer the images to the "tf_files/data" folder



### Run the retrain script ###

##### Navigate to the directory in terminal and run : #####

```console
chmod 700 retrain_on_data.sh
./retrain_on_data.sh
```

### Test the retrained model ###

##### To test on custom images, just change the image name on the last line of the "check_label.sh" script #####
##### ie, change "test4.jpeg" on the 3rd line to image name #####

```console
chmod 700 check_label.sh
./check_label.sh
```










## TO do :

### Include CIFAR 10 reference ###
### include Galaxy Zoo reference ###
### Include tensorflow for poets ###