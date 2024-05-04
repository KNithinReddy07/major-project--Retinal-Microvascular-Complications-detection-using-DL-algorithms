# PROJECT NAME :  RETINAL MICROVASCULAR COMPLICATIONS DETECTION USING DEEP LEARNING ALGORITHMS

# PROBLEM STATEMENT:
 Diabetic Retinopathy, a condition with an escalating prevalence, stands as the primary cause of vision impairment among the working-age populace. The risk of severe vision loss can be significantly mitigated through timely diagnosis and treatment. Systematic screening for Diabetic Retinopathy has been recognized as a cost-effective strategy, conserving healthcare resources. Automated analysis of retinal images is emerging as a pivotal screening mechanism for early detection of Diabetic Retinopathy. This approach not only alleviates the manual grading burden but also economizes diagnosis time and expenses. Over recent years, substantial research endeavors have been dedicated to crafting automated tools aimed at aiding in the detection and assessment of Diabetic Retinopathy lesions.

# PROPOSED SYSTEM: 
A novel approach to detect diabetic retinopathy using Xception, Densenet201,Inception V3 and IR-CNN from fundus images. The proposed model is evaluated on a pub- licly available dataset of fundus images.additionally conduct experiments with im- age enhancement and data augmentation methods to improve the performance of the proposed model.

# DATASET:
[https://www.kaggle.com/datasets/vuppalaadithyasairam/fundus-images-for-diabetic-retinopathy ](url)

# WORKFLOW:
1. Importing the packages
2. Exploring the dataset 
	- Diabetic Retinopathy Classification
3. Image processing
	- using ImageDataGenerator 
		- Re-scaling the Image
		- Shear Transformation
		- Zooming the Image
		- Horizontal Flip 
		- Reshaping the Image 
	
	
4. Building the model 
    - ResNet50
    - InceptionV3
    - InceptionV3 and ResNet50 Combination with CNN
    - DenseNet201
    - Xception
5. Training the model
6. Building the model 


Flask Framework
 
7. Flask Framework with Sqlite for signup and signin
8. Importing the packages
9. User Upload an image for analysis
10. The given input is preprocessed 
11. The trained model is used for predicting the result
12. Final Outcome is display
