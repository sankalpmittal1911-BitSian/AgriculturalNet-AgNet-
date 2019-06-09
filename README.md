# AgriculturalNet-AgNet
State of the art model for classifying 256 crop categories built in Keras.

# Basic Architecture Used: 
U-Net

# Dataset:
https://github.com/ZihengSun/Ag-Net-Dataset

# Color Map:
https://github.com/ZihengSun/Ag-Net-Dataset/blob/master/colormap.py

After training for 1000+ epochs, I was able to get training accuracy of about 91% and validation accuracy of 84%.

# True Image
![](https://github.com/sankalpmittal1911-BitSian/AgriculturalNet-AgNet-/blob/master/Images/54494876-ced0d480-4904-11e9-9efc-4cec8976b72c.png)
![](https://github.com/sankalpmittal1911-BitSian/AgriculturalNet-AgNet-/blob/master/Images/Generated_Mask%20(1).png)

# Predicted Image
![](https://github.com/sankalpmittal1911-BitSian/AgriculturalNet-AgNet-/blob/master/Images/54494876-ced0d480-4904-11e9-9efc-4cec8976b7new2c.png)
![](https://github.com/sankalpmittal1911-BitSian/AgriculturalNet-AgNet-/blob/master/Images/Generated_Mask.png)

# Changes to U-Net block:

1. Use of skip connections.

2. Use of GlobalMaxPool2D instead of MaxPool2D.

3. Use of Spatial Excitations.

4. Use of PRelu and Leaky Relus.

Scope of improvement: Yes!

Please feel free to suggest tips for improvement!

# Suggested Tips:

1. Use class weights.

3. Use Custom Image Augmentation on Tranining Data.

2. Try other models like PSPNet.

Contribute as much as possible!

Cited here: https://github.com/ESIPFed/Ag-Net
