# Data-Augmentation-Arguments-keras--Explained
Real-time data augmentation properties are used to generate the images when dateset is limited.Certain arguments are available in Keras to generate images with different properties.

ImageDataGenerator class is used to generate images using data augmentation.

Arugments of ImageDataGenerator Class is explained step by step,so one will be able to use them to generate dataset.
Arugments are explained as follows

1.ROTATION
this angle would help to rotate the image between the negative to positive range described by us.For example in present case
it would rotate the image between 60 to -60

2.WIDTH-SHIFT AND HEIGHT SHIFT
It would help us to shift the image between the described range

3.BRIGHTNESS
it is use to control the brightness range of the images

4.ZOOM
Zoom the image to any value given below i.e between 0.5 to 2.0

5.SHEAR TRANSFORMATION
Image will be distorted along the axis

6.CHANNEL SHIFT
It would randomly shift the channel value by the mentioned channel shift range
7.FLIPS
Images would be randomly flipped on vertical and horizantal axis

8.NORMALIZATION
When features in a dataset have different range of values,in ML,we use technique known as normalization.Normalization
change the values numeric columns in dataset to a common scale
Standard deviation is use to normalize the data
SD tells us about spreat out of values.LOW SD most number are close to mean value
Formula for SD is  x.mean=x_train.mean()  x.train_norm=x.train.std()     x_train_norm=(x_train-x_mean)/x.std()

a)Featurewise Normalization
Featurewise , data is mostly normalized feature-wise as the aim is to study relationship across samples
and being able to predict well about new samples

b)Samplewise Normalization
Samplewise normalization take each sample and normalize it's features such as the end up being a unit vector
