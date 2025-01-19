**Week-5**

This will be your final project for WiDS. You are assigned two parts to work on. While it is recommended to complete both, it is acceptable to focus on just one of them.

**PROJECT 1**
Make a CNN architecture and train it for CIFAR100 classification
> Architecture should not be exactly same as of existing famous architectures like : LeNet-5, Alexnet etc. You can make your own inspired from them.
> **If it takes time in training, you can use free GPU available on google colab and if GPU units get exausted on you one google accoount, you can use anohter google account for training :)**

> Accuracy should be more than 60%

 Plot necessary graphs related to training model 

**Project 2**

Brightness Controller + The color of brightness level/bar should change from green (bright) to red (dim)

For Brightness you can use wmi library
>import wmi

Initialize WMI for brightness control

>c = wmi.WMI(namespace='wmi')

Set monitor brightness using WMI
>brightness = int(length)     //length is distance between fingers

>c.WmiMonitorBrightnessMethods()[0].WmiSetBrightness(brightness, 0)  # Set brightness
