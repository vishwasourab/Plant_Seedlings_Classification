    ----------------------------------------------------------------------------------
    ----------------------------------------------------------------------------------

                      Plant Seedling Classification Project  
                      Machine Learning Engineer Nanodegree 

                          *** Brungi Vishwa Sourab ***
                                 November 2018
    ----------------------------------------------------------------------------------
    ----------------------------------------------------------------------------------

    ----------------------------------------------------------------------------------
                                      Dataset
    ----------------------------------------------------------------------------------

    The Plant Seedlings Dataset contains images of approximately 960 unique plants belonging 
    to 12 species at several growth stages. It comprises annotated RGB images with a physical 
    resolution of roughly 10 pixels per mm.

    The database have been recorded at Aarhus University Flakkebjerg Research station in a 
    collaboration between University of Southern Denmark and Aarhus University.

    We hope that the database will provide researchers a foundation for training weed recognition 
    algorithms. For more info about dataset, see the dataset description paper 
    (http://arxiv.org/abs/1711.05458)

    ----------------------------------------------------------------------------------
                                Dataset Download Links
    ----------------------------------------------------------------------------------
    RAW Images (9.7 GB) (https://vision.eng.au.dk/?download=/data/WeedData/Fullimages.zip)
 
    Cropped Plants V2(1.7GB) (https://vision.eng.au.dk/?download=/data/WeedData/NonsegmentedV2.zip)
 
    Cropped Plants V1(1.7GB) (https://vision.eng.au.dk/?download=/data/WeedData/Nonsegmented.zip)
    
    ----------------------------------------------------------------------------------
                                Requirements
    ----------------------------------------------------------------------------------
    
    Keras
    PIL
    cv2
    ----------------------------------------------------------------------------------
                                Dataset Structure
    ----------------------------------------------------------------------------------
    |data
    | -train
    |     - (all species folders)