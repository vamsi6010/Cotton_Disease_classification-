# Cotton_Disease_Classification
 
The country's economic prosperity is heavily dependent on crop output quality and quantity. Leaf disease diagnosis at the right moment can increase output profit. For the diagnosis of leaf disease, many image processing approaches have been developed. At an early stage, technological advancements make the process easier and faster. One of the most serious problems in agriculture is leaf disease. Cercospora, Bacterial blight, Ascochyta blight, and Target spot are diseases that harm cotton leaves. Farmers' general observations might be time-consuming, costly, and erroneous. For this, we provide a Deep Convolutional Neural Network-based technique for autonomously detecting Cotton leaf illnesses. Deep Convolutional Neural Network is being employed  to identify cotton leaf disease, according to our knowledge.


## Pacages used
1. Tensorflow 
2. Keras
3. Numpy 
4. Glob 
5. Matplotlib


## Dataset count
| Test Data   |Count | Train data  | Count   | Validation   | count | Total | 
| ------------- | ------------- |------------- |------------- |------------- |------------- | ------------- |
| Diseased cotton leaf   | 3  | Diseased cotton leaf  | 288  | Diseased cotton leaf  |   55 | 346 |
| Diseased cotton plat  | 5  | Diseased cotton plat  | 815  | Diseased cotton plant|101 | 921|
| fresh cotton leaf  | 5  | fresh cotton leaf  | 427 | fresh cotton leaf | 80| 512|
| fresh cotton plant   |5 | fresh cotton plant  |   421 | fresh cotton plant   | 88| 514|
| Total   |18 | Total  |   1,951 | Total   | 324 | 2,293|


# Total no of Parameters
| Parameters | No of parameters|
| ----------| ------------------|
|Trainable Parameters | 208, 804|
|Non - Trainable Prameters| 21,802,784|
|Total Parameters | 22,007,588|

## Accuracy
|Accuracy | 94%|
|---------------|-----------|
## Transfer Learning
Transfer learning is a machine learning technique in which a model created for one job is utilised as the basis for a model on a different task.

It is a popular approach in deep learning where pre-trained models are used as the starting point on computer vision and natural language processing tasks given the vast compute and time resources required to develop neural network models on these problems and from the huge jumps in skill that they provide on related problems.


![This is an image](https://cdn-images-1.medium.com/max/1000/0*xNjEPIZmPvKeqss6)


In transfer learning, we first train a base network on a base dataset and task, and then we repurpose the learned features, or transfer them, to a second target network to be trained on a target dataset and task. This process will tend to work if the features are general, meaning suitable to both base and target tasks, instead of specific to the base task. For this model we used inceptionV3 model pretrained on imagenet weights.

## Inception v3

Inception V3 by Google is the 3rd version in a series of Deep Learning Convolutional Architectures. Inception V3 was trained using a dataset of 1,000 classes (See the list of classes here) from the original ImageNet dataset which was trained with over 1 million training images, the Tensorflow version has 1,001 classes which is due to an additional "background' class not used in the original ImageNet. Inception V3 was trained for the ImageNet Large Visual Recognition Challenge where it was a first runner up.

![This is an image](https://cloud.google.com/tpu/docs/images/inceptionv3onc--oview.png)
