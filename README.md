# ML_brain_tumor
## Brain Tumor Detection Using Machine Learning CNN Architecture
Early diagnosis is essential in brain tumors, which divides into three parts, benign, pre- malignant, and malignant. Thousands of people around the globe, from children to adults, are diagnosed with brain tumors every year, and it causes the death of some of them. Timely and prompt disease detection using Magnetic Resonance Imaging (MRI) may increase the rate of survival of the patients and also causes an increase in the quality of life and life expectancy in these patients. In MRI, the process can be conducted more smoothly because it shows the tumor clearly. Recently, brain tumors, with the assistance of Machine Learning, can be diagnosed easily through magnetic resonance imaging. In this manuscript, a Deep Learning model based on a Convolution Neural Network (CNN) is used to diagnose a brain tumor and classify its type. Since the lack of data, data augmentation is applied to train the neural network effectively. The following preprocessing steps are applied for every MR image: image cropping, image resizing, and implementing normalization to scale pixel values to the range 0-1. The data was divided into three categories: training, validation, and testing. Finally, the model is trained, and the results show 88.7% accuracy on the test set.

**Original image and after cropping was applied.**

![cropped_image](https://github.com/elif-t/ML_brain_tumor/blob/main/cropping.png)

**Images after data augmentation was applied.**

![augmented data](https://github.com/elif-t/ML_brain_tumor/blob/main/augmented_data.png)

**Images with non-tumors.**

![no brain tumor](https://github.com/elif-t/ML_brain_tumor/blob/main/brain_tumor.png)

**Images with tumors.**

![yes brain tumor](https://github.com/elif-t/ML_brain_tumor/blob/main/yes_tumor.png)
