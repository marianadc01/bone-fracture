# PML Final Project - Bone Fracture Identificatiom                        
### Created by: Maria Dolgaya (28168) and Mariana Coelho (25605)  
### Professor Manuel Lameiras de Figueiredo Campagnolo            
### MSc in Green Data Science, ISA, Portugal 

For our final project for the class Practical Machine Learning, we have decided to create a model that identifies in a set of images if there's a bone fracture or not and in which area of the body does it occur.

**Project category:** image classification

**Information:**
- Problem Statement: What problem will you be investigating? Why is it interesting?
  
The problem is based on the bone fracture multi-region x-ray dataset, which is composed of fractured and non-fracture x-ray images of all anatomical body regions (lower limb, upper limbs, lumbar area, knees, etc. The goal of this project is to build an image classification model (similar to the corn leaf disease detection example given in class), and maybe build a space in HuggingFace with it.

- Challenges: What are the challenges of this project?
  
There’s a large quantity of images in the data set, which can be challenging. Also, the model might not be able to correctly identify the areas in which the fractures can occur, or even if there is one because of the images colours (the grey and black can cause some shading and mislead the model).

- Dataset: What dataset are you using? How do you plan to collect it? You can use your own data or gather data from online data repositories.
  
We’re using the [Bone Fracture Multi-Region X-ray Dataset](https://www.kaggle.com/datasets/bmadushanirodrigo/fracture-multi-region-x-ray-data) 
