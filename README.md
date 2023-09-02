# Image_Restoration_Model

**Problem Statement** - In the domain of art restoration, develop an innovative computer vision model capable of effectively restoring deteriorated images of art pieces. The goal is to create an automated solution that can enhance and reconstruct degraded artworks, improving their visual quality while preserving their original characteristics. The model should handle a diverse range of deterioration types, including but not limited to noise, blur, scratches, fading, and other common forms of degradation.

We as a Team have created an Image Restoration Model implementing Convolutional Neural Networks and utilizing the principles of Sequential Learning. This model can be used to restore deteriorated images to a better quality. The Model has a max accuracy of 90%, while the average floats around 86%.

**Skills Used** - Python, OpenCV, TenserFlow, Keras, Deep Learning, Machine Learning, Data Collection, Data Manipulation, Data Processing.

**Crew Team Process Summary on Image Restoration Model Creation.**
  Team Tageline: In a relentless pursuit to administer a solution to the Universal problem.
  **Team Members**
  D.Bippin Shekar Goud: - Team Leader and Lead Coder, Machine Learning Engineer
  M Sai Trilochan: - Data Preparation, Data Visualization, and Data Processing
  D Suddin Shekar Goud: - Data Collection, Web Scraping, Report preparation
  
  **Course of Action**:
  
  1. **Step 1 - Data collection**.
    Data Collection was the first major milestone in our project creation journey.

      ***a***. This step required us to scrape the internet to acquire the images that can be utilized. After, collection the next sub-step is to process the data   
               according to our problem statement requirements, which required us to prepare the data. Data Preperation step consisted of applying the required blur, 
               noise, scratches, and water spill effects.


      ***b***. Acquiring around 10,000 data points and performing data pre-processing tasks on these images, this one was of the hardest challenges face during the project 
               devlopment phase, as it was computationally expensive.
             
  2. **Step 2- Data Pre-Processing**.
     The Data Pre-Processing steps contain the resizing and the normalization of all the images in our respective data sets. After passing the data through the resizing and
     normalization functions, we enter the step of splitting the data into training and testing data. After performing the splitting, using the train_test_split model from
     SKlearn, we perform stack operation on the x_train, x_test, y_train, and y_test, from the 10,000 data points we have allocated 20% of it to validations sets.Stacking 
     is a crucial step as the data that has to be fed to out model takes only 1 Input.
     
  3. **Step 3 - Model Creation**.
     We have arrived at the step of creation of the Convolutional Neural Network that will help us image restoration. We utilized the process of sequential learning to 
     train our model to detect and restore any image deterioration. Conv2d, MaxPooling2d, Concatenate, UpSampling2d have been used from tensorFlow.keras layers to build 
     the Neural Network.
     
  5. **Step 4 - Model Training and Testing**.
     After the creation of our model, we compile the model by running the model using different optimizers, loss functions, and metrics, then finally settling on the ones 
     that provide the best performance, based on the blemishes we are trying to rectify. Then, we enter into the training and testing phase, which includes calculating the 
     model's accuracy.
     
  6. **Step 5 - Data Post-Processing**.
     This step comprised the steps of denormalizing and re-sizing the images into their original form.
     
  7. **Step 6** - Saving the Model and Processed Data.
     Now we have arrived at the final milestone of saving these post-processed output images into the respective folders.

**Model Performance**:The highest performance accuracy is 90% while the average accuracy of the model floats around 86%.
