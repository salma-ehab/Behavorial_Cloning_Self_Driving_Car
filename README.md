# Behavorial_Cloning_Self_Driving_Car
Driving a car autonomously by building a model using convolutional neural network to output a steering  angle to the car to keep it on the road for at least one lap.

Pre-processing the images that were used for training:
* The parts of the images which contained the hood of the car and past the horizon were removed as they are unnecessary. 
* The images were resized to 64 by 64 so that the time needed for training is reduced. 

Augemntation of the images that were used for training:
* Flipping them horizontally half the time where the angle is altered accordingly, so that the model is able to evenly train left and right.
* Shearing the images horizontally 90% of the time, so that a bending road is simulated by letting the pixels at the bottom of the image remain fixed while the pixels at the top row are moved randomly to the left or right.
* Altering the brightness of the images randomly to simulate different lighting conditions.
* After preprocessing the images, the images were shifted vertically randomly to simulate the road in the second track.




