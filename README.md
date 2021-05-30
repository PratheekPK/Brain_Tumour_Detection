# Brain_Tumour_Detection
Comparison of the DenseNet, Resnet and EfficientNetB4 architectures for image classification on the Kaggle Brain Tumour dataset.

	With the DenseNet architecture I was able to achieve a extremely high accuracy of 96 percent on the validation dataset which is among the highest for the kaggle dataset.

Preprocessing:

	Firstly I converted the image from the BGR format to the RGB format using the computer vision library.
	Next, I cropped the dark edges from the image so as to delete unrequired information.
	Then, I resized the image to 255x255.
	Finally, I applied Gaussian blurring to the image.

I used the ImageDataGenerator function in order to rescale, rotate and flip the image and do data augmentation.

Finally I created the DenseNet, ResNet and EfficientNetB4 architectures to carry out the Image Classification job.


