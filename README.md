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

**Output shapes after layers applied to the images.**

![layer](https://github.com/elif-t/ML_brain_tumor/blob/main/layer.png)

### Results and Discussion

An approach for brain tumor classification is presented by applying a CNN model to MR images. The Cancer Genome Atlas Low-Grade Glioma (TCGA-LGG) that contained images from 110 participants and three different types of image acquisition sequences are used in this examination and classified into two classes where class 1 refers to tumor images and class 0 refers to non-tumor images. Eight different data augmentation methods are applied. After data augmentation, data pre-processing, and data splitting, the number of training samples is 1445, the number of validation samples is 310, and the number of test samples is 310. The final output of the proposed method using 22 numbers of epochs. First figure below, the corresponding loss is shown, and the training and validation accuracy concerning the number of epochs can be seen in second figure below. The reason that this model is applied is computational complexity and memory limitations are considered.

**The training and validation loss across the epochs.**

![The training and validation loss across the epochs.](https://github.com/elif-t/ML_brain_tumor/blob/main/graph1.png)


**The training and validation accuracy across the epochs.**

![The training and validation accuracy across the epochs.](https://github.com/elif-t/ML_brain_tumor/blob/main/graph2.png)

### Conclusion 

Finally, results were quite nice, model gave the 86.1% testing accuracy on testing samples and 0.86 f1 score on the test set. 


