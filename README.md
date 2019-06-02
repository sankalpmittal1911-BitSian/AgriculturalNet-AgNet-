# AgriculturalNet-AgNet-
State of the art model for classifying 256 crop categories built in Keras.

# Basic Architecture Used: 
UNet

After training for 1000+ epochs, I was able to get training accuracy of about 91% and validation accuracy of 84%.

Changes to UNet block:

1. Use of skip connections.
2. Use of GlobalMaxPool2D instead of MaxPool2D.
3. Use of Spatial Excitations.
4. Use of PRelu and Leaky Relus.

Scope of improvement: Yes!

Please feel free to suggest tips for improvement!

Suggested Tips:

1.Use class weights.
2. Try other models like PSPNet.

Contribute as much as possible!

