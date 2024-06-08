# PML Final Project - Bone Fracture Identificatiom                        
### Created by: Maria Dolgaya (28168) and Mariana Coelho (25605)  
### Professor Manuel Lameiras de Figueiredo Campagnolo            
### MSc in Green Data Science, ISA, Portugal 

For our final project for the class Practical Machine Learning, we have decided to create a model that identifies whether there is a bone fracture in a set of images.

**Project category:** image classification

**Information:**
- Problem Statement: What problem will you be investigating? Why is it interesting?
  
The problem is based on the bone fracture multi-region x-ray dataset, which is composed of fractured and non-fractured x-ray images of all anatomical body regions (lower limb, upper limbs, lumbar area, knees, etc). The goal of this project is to build an image classification model (similar to the corn leaf disease detection example given in class), and build a space in HuggingFace with it. This task is interesting because it has potential to improve diagnostic efficiency and accuracy in medical settings. 

- Challenges: What are the challenges of this project?
  
1. Computational Resources: There’s a large quantity of imagery files in the data set, which can be challenging for the model.
2. Similarities in colors: The grayscale nature of X-ray images can cause some shading and mislead the model. 
3. Quality: The quality and variability of the images is another challenge as the images represent different anatomical regions and presence of noise can also affect the model performace.
4. Overfitting: The high dimensionality of image data can cause overfitting.

- Dataset: What dataset are you using? How do you plan to collect it? You can use your own data or gather data from online data repositories.
  
We’re using the [Bone Fracture Multi-Region X-ray Dataset](https://www.kaggle.com/datasets/bmadushanirodrigo/fracture-multi-region-x-ray-data), which incorporates training (9246 images), testing (506 images) and validation (828 images) data. This dataset is sourced from Kaggle and includes necessary metadata regarding licensing and author credits. 

- Method or Algorithm: What method or algorithm are you proposing?

1. Data preprocessing: normalisation, augmentation techniques on the training data (rotation, flipping etc.)
2. Model development and architecture: pre-trained Convolutional Neural Network (e.g. ResNet) and custom layers on top of it
3. Training: loss function, optimizer (Adam)

- Evaluation: How will you evaluate your results? What kind of analysis will you use to evaluate and/or compare your results (e.g., performance metrics or statistical tests)?

For this project, the accuracy for each epoch will be calculated and the model that will perform classification with the best score will be saved for future deployment. 