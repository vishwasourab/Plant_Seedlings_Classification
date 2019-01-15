# Plant Seedlings Classification

### Introduction:

For several years, many people have tried to solve the problem of identifying weeds. They used wide range of approaches with the common goal of identifying weeds from normal plants but no system that has made a commercial breakthrough has been developed. There are various reasons for these systems to be not able to solve the problem. One of them is data collection. A research paper on similar problem identifying plant species by the shape of leaf is published by Ji-Xiang Du, Xiao Feng Wang & Guo-Jun Zhang, Department of Automation, University of Science and Technology of China.

I strongly believe that this problem can be solved using deep learning because the technology(hardware) is capable of doing image identification tasks easily and now is the right time for such breakthrough systems because of the latest techniques in deep learning. Until very recently, the main problem was acquisition of the image data to be used to build robust systems. But, in November of 2017, to support and encourage the development of species recognition techniques for the agricultural industry, the Computer Vision and Biosystems Signal Processing Group, Department of Engineering, Aarhus University has collected the data and made it available to the public for free.

### Problem Statement:

Differentiating a weed from a crop seedling by the image can pave a significant way to intelligent weed control systems and thus eliminating the unwanted plants in its initial stages only. The ability to do so effectively can mean better crop yields and better stewardship of the environment. The Aarhus University Signal Processing group, in collaboration with University of Southern Denmark, has recently released a dataset containing images of approximately 960 unique plants belonging to 12 species at several growth stages. My goal is to build a classifier that classifies the seedling’s class based on the image input, using state of the art deep learning techniques.

### Workflow:

The details and the workflow is listed below:
* Exploring the data
  * Importing libraries and data
  * View a sample of training data
  * View number of images in training data
  * View species vise images count
* Data Preprocessing
  * Transforming Images (Resize, Converting to Arrays, Normalizing)
  * Splitting data for training and Validation
* Model Building
  * Basic CNN for benchmarking
  * Complex CNN architectures
  * Hyperparameter Tuning
  * Training and Validating the models
  * Saving best model and weights to disk
* Algorithm Building
  * Creating a pipeline for image classification
  * Loading and predicting the class on saved model
  
### Requirements:
```
Keras(tensorflow)
PIL
CV2
```
### Results:
The results of our classifier are sufficient enough for the problem we are solving. Mainly, the
classifier we built gave a very good accuracy in identifying weed plants, which was the main
goal of our project. So, I strongly believe this model can be used as an application in detecting
weed plants when they are small and significantly boost farmers productivity

| Benchmark Score  | Our Model Score | % of improvement |
| -------------    | -------------   | ------------- |
| 0.578            | 0.936           | 61.9  |
