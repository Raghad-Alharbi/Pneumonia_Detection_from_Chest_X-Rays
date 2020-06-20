![](data:image/png;base64,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 )


# Pneumonia Detection from Chest X-Rays


<img src="https://miro.medium.com/max/1400/1*rZ8wn3AO4CtzW_DGSQJjPg.png" style="height: 250px; width: 1200px">

### AI for Healthcare Nanodegree Program
**Project 1**
---

# FDA  Submission

**Your Name:** Raghad Alharbi

**Name of your Device:** Deep Pneumo Detector

## Algorithm Description 

### 1. General Information

**Intended Use Statement:** 

This algorithm is intended for use in assisting a radiologist with the detection of the presence of pneumonia in a chest X-rays  screening.

**Indications for Use:** 

This algorithm is indicated for use in screening chest X-Ray studies of pneumonia in men and women of ages 1-95 with posteroanterior (PA) or anteroposterior (AP) views. The algorithm should be integrated into the normal workflow of the diagnostic clinics. The X-Ray images should be available in DICOM format, respecting the HIPAA rules. The data is then sent through your algorithm and it first checks the conditions. If it satisfies the criteria, it makes the prediction. Once the prediction is complete, this data is sent to a radiologist, and then he/she will give the final decision based on his/her independent diagnosis as well as the data supplied by your algorithm.

**Device Limitations:** 

This algorithm is not appropriate to be use in emergency sittings because of its performance based limitations. This algorithm needs a GPU to preforme well.

**Clinical Impact of Performance:** 

The algorithm was designed to have higher F1 score and high recall which means there may be more false positive. This means it is more likely for the algorithm to classify a non-pneumonia x-ray image as having pneumonia. The algorithm can also produce false negative result where xray image with pneumonia may be classified as not having pneumonia, which is not an intended outcome, and can be a life threat if the predition was taken into consideration without any further assessment by a Radiologist.

### 2. Algorithm Design and Function

**Algorithm Flowchart**

![](assets/diagram.png)

**Diagram Steps:**

* Read and Check DICOM files
* Split training and validation datasets
* Rebalance and image augmentation for train set
* Build CNN from a VGG16 base model and some extra layers
* Evaluate CNN performance  
* Set threshold to maximize F1 score
* Predict Pneumonia

**DICOM Checking Steps:**

1. The Algorithm reads in DICOM File.
2. Extracts Patient and picture information.
3. Checks if Modality is 'DX'.
4. Checks if Patient Age is less than 100.
5. Checks if Body Part Examined is 'Chest'.
6. Checks if Patient Position is either 'PA' or 'AP'.

**Preprocessing Steps:**

1. Image is resized to 224 x 224 pixles.
2. Image intensity is normalized.

**CNN Architecture:**

- The base model is a [VGG16](https://keras.io/api/applications/vgg/) model that was pre-trained on Imagenet data. 
- Extra layers has been added to the top of the base model:
    - Flatten
    - Dropout with 30% probability
    - Dense, 1024 units with ReLU activation
    - Dropout Dropout with 30% probability
    - Dense, 512 units with ReLU activation
    - Dropout with 30% probability
    - Dense, 256 units with ReLU activation
    - Dropout with 30% probability
    - Dense, 1 unit with Sigmoid activation

### 3. Algorithm Training

**Parameters:**

- Types of augmentation used during training:
    - rescale=1. / 255.0 
    - horizontal_flip = True 
    - vertical_flip = False 
    - height_shift_range = 0.1
    - width_shift_range =0.1 
    - rotation_range =10 
    - shear_range = 0.1
    - zoom_range=0.1   
- Types of augmentation used during validation:
    - rescale=1. / 255.0
- Batch size:
    - Training set batch size = 128 images
    - Validation set batch size = 1000 Images
- Optimizer learning rate: 1e-4
- Layers of pre-existing architecture that were frozen:
	- The first 17 layers of the VGG16 base model 
- Layers of pre-existing architecture that were fine-tuned: 
	- All layers other than the first 17 layers 
- Layers added to pre-existing architecture:
    - Flatten
    - Dropout with 30% probability
    - Dense, 1024 units with ReLU activation
    - Dropout Dropout with 30% probability
    - Dense, 512 units with ReLU activation
    - Dropout with 30% probability
    - Dense, 256 units with ReLU activation
    - Dropout with 30% probability
    - Dense, 1 unit with Sigmoid activation

**Algorithm training performance visualization:**

![](assets/Preformance.png)

**AUC and P-R Curve:**

![](assets/AUC.png)

**Final Threshold and Explanation:**

Threshold of 0.41005385 was chosen based on the best F1 score, which was 0.417910
![](assets/F1.png)

* Accuracy = 0.727
* Precision = 0.3333333333333333
* Recall    = 0.56
* F1 Score  = 0.41791044776119407
* Sensitivity = 0.56
* Specificity = 0.7624242424242424

**Confusion Matrix:**

![](assets/CM.png)

### 4. Databases

This NIH Chest X-ray Dataset contains 112,120 X-ray images with disease labels from 30,805 unique patients. The disease labels were created using Natural Language Processing (NLP) to mine the associated radiological reports. The labels include 14 common thoracic pathologies:

* Atelectasis
* Consolidation
* Infiltration
* Pneumothorax
* Edema
* Emphysema
* Fibrosis
* Effusion
* Pneumonia
* Pleural thickening
* Cardiomegaly
* Nodule
* Mass
* Hernia

Some statistics about all patients in the dataset:

**All patients in the dataset:**

![](assets/Findings-1.png)

![](assets/diseases.png)

The population is highly imbalanced between pneumonia and non-pneumonia cases. There are total of 110689 samples with no pneumonia, and 1431 samples with pneumonia in the dataset. 

![](assets/Pneumonia.png)

The patient population for these images were 1-95 year olds and 56.5% male and 43.5% female. 

![](assets/all_ages.png)

![](assets/gender_all.png)

Some statistics about Pneumonia patients in the dataset:

**Pneumonia patients in the dataset:**
![](assets/Findings-2.png)

![](assets/disease-pneu.png)

![](assets/age-both.png)

![](assets/gender_Pnemonia.png)


**Description of Training Dataset:** 

80% of the full dataset was selected to be in the training dataset. There are 2288 images in the train dataset after balancing the two classes.
Prevelance of Pneumonia is 0.5.
Number of  pnuemonia  cases in the train data is 1144.
Number of  non-pneumonia  cases in the train data is 1144.
 
Example of the images in the train dataset after augmentation and their labels:

![](assets/x-rays.png)

**Description of Validation Dataset:** 

20% of the full dataset was selected to be in the validation dataset.There are 1716 images in the valid dataset.
Prevelance of Pneumonia is 0.166.
Number of  pnuemonia  cases in the valid data is 286.
Number of  non-pneumonia  cases in the valid data is  1430.

### 5. Ground Truth

To create these labels, the authors used Natural Language Processing to text-mine disease classifications from the associated radiological reports. The labels are expected to be >90% accurate and suitable for weakly-supervised learning. The original radiology reports are not publicly available but you can find more details on the labeling process in this Open Access paper: "ChestX-ray8: Hospital-scale Chest X-ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases." [(Wang et al.)](https://www.nih.gov/news-events/news-releases/nih-clinical-center-provides-one-largest-publicly-available-chest-x-ray-datasets-scientific-community)


### 6. FDA Validation Plan

**Patient Population Description for FDA Validation Dataset:**

The sample population of the FDA validation dataset should digital X-ray images from the chest area that are taken from men and women distributed between the age of 1 and 100 with with posteroanterior (PA) or anteroposterior (AP) views.


**Ground Truth Acquisition Methodology:**

As a silver standard for validating X-ray images,we need at least 3 independent practicing radiologists to create the labels. The final diagnosis is then determined by a voting system across all of the radiologists’ labels for each image. The silver standard method is discribed in the ["CheXNet: Radiologist-Level Pneumonia Detection on Chest X-Rays with Deep Learning" paper](https://arxiv.org/pdf/1711.05225.pdf).

**Algorithm Performance Standard:**

Similar to the CheXNet study, We calculate the algorithm’s F1 score and F1 Scores of the silver standard method produced by the voting of three radiologists' diagnosis. Then, both are compared to determine the performance of the algorithm compared to the radiologists.