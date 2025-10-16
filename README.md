# MNIST-AI
# **README**
#Tobechi Nwachukwu
#Stephen Akinpelu 
#Kendall Daze-Yach

#This Code is designed for AI training only, it will save the AI on train and load for testing but,
#It is NOT designed for segmented or repeated training and thus, will not load the AI prior to training

#This is a test to investigate the usefulness of two-part segmented AI architectures working together-
#To solve a more complex problem.

#Is it better to train an AI specifically for a dataset or can this be streamlined using pre-processing functions?

# **PLEASE ENSURE ALL DATA IS CREATED WITH MNIST_noise_creation.ipynb BEFORE RUNNING THIS NOTEBOOK**

Steps to run:

1. Please ensure environmment coontains all required libraries (pytorch, matplot...)

2. Please have all notebooks and .pth documents in the same folder.

3. Run MNIST_noise_creation.ipynb to load the MNIST dataset and generate the "noised dataset", this has been provided as code instead of an uploaded partial dataset to brightspace.

4. It is now okay to run Full_Architecture.ipynb. This is a segmented notebook with each test outlined in our report separated for convenience. You do not need to run every single segment.

5. Please run all code above # MNIST Standalone to properly run the functions below

6. The .pth model files have been provided if you would like to skip to test only segments.  

7. It is highly reccomended that CUDA cores are used to process the architecture. If runtime issues are a problem increasing batch size or reducing epoch count will help but, will lead to accuracy costs.
