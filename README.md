# Retinal-Vessel-Segmentation-with-UNET
Segmentation of Retinal Vessels using the UNET architecture

In this project we have firstly taken a small dataset of Retina images and used data augmentation on those images to improve the training. We have then referred to the UNET research paper and created the neural network from scratch using Pytorch. After using various performance metrics we have determined the accuracy of the model on the given dataset. Finally the model was made to make some predictions on Retina images which were compared to the original masks. The results were stored in a separate folder for further research and analysis. This project helps us understand the importance of Data Augmentation for a segmentation problem using UNET. It also shows the implementation of UNET from scratch with reference to its research paper. Finally, it helps present the significance of UNET when it comes to segmentation problems in the medical field.

U-NET : A Deep Learning Algorithm for Image Segmentation

1.	U-NET is a deep learning algorithm that is widely used for image segmentation tasks. It is a fully convoluted network (FCN) that is based on supervised learning technique.
2.	U-NET uses a combination of convolutional and upsampling layers to generate a high-resolution segmentation map from an input image. The architecture of the U-NET model consists of a contracting path and an expanding path, where the contracting path extracts features from the input image and the expanding path uses these features to generate the final segmentation map.
3.	U-NET is particularly useful for medical imaging and biomedical image analysis tasks where accurate segmentation is crucial. The model is trained on annotated images, and the weights of the model are updated during the training process.
4.	One of the key features of U-NET is that it leverages skip connections between the contracting and expanding paths, which helps to preserve fine details in the segmentation maps.
Example : Suppose, we have a medical image of a brain and we want to segment the different regions of the brain such as the gray matter, white matter and cerebrospinal fluid. We can use the U-NET algorithm to solve this problem as it is well suited for image segmentation tasks. Our U-NET model will learn the features of different regions in the training images and apply those features to generate a segmentation map of the input image.

Why do we need a U-NET Algorithm?
U-NET is used in a variety of applications where accurate segmentation is critical, such as medical imaging, object detection, and image restoration. The U-NET architecture allows for a balance between the localization of fine details and the global context of the image, making it a valuable tool for image segmentation tasks.

How does U-NET work?
The working of U-NET can be explained on the basis of the following steps:
Step  1 : Input an image
Step  2:  The image is passed through a series of convolutional and pooling layers in the contracting path to extract features from the input image.
Step 3: The features are then passed through a series of upsampling and concatenation layers in the expanding path to generate a high-resolution segmentation map.
Step 4: The final segmentation map is compared to the annotated ground truth and the weights of the model are updated during the training process.
Step 5: The model is then used to generate a segmentation map for new images.

Advantages of U-NET Algorithm:
•	It proves high-resolution segmentation maps.
•	It is suitable for medical imaging and biomedical image analysis tasks where accuracy is crucial.
•	It leverages skip connections to preserve fine details in the segmentation map.

Disadvantages of U-NET Algorithm:
•	The architecture of the U-NET model is complex and requires a large number of parameters to be trained.
•	It may struggle to preserve fine details in images with large objects or complex shapes.
•	The training process can be computationally expensive.
