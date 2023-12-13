**Image Augmentation** is the technique that can artificially enlarge the diversity and size of a dataset. It does so by applying a number of alterations on the images. These changes include rotation, flipping, scaling, translation, changes in brightness and contrast, etc. The goal is to increase the generalization and robustness of ML models by exposing them
to variants that may occur in real-world data. It includes making minor changes to the dataset or using deep learning to generate new data points.

Need of Augmentation:
1.To prevent models from overfitting.  
2.The initial training set is too small.  
3.To improve the model accuracy.  
4.To Reduce the operational cost of labeling and cleaning the raw dataset.

There are vareity of Image Augmentation techniques some of them are:
1. Geometric transformations: randomly flip, crop, rotate, stretch, and zoom images. You need to be careful about applying multiple transformations on the same images, as this can reduce model performance. 
2. Color space transformations: randomly change RGB color channels, contrast, and brightness.
3. Kernel filters: randomly change the sharpness or blurring of the image.
4. Random erasing: delete some part of the initial image.
5. Mixing images: blending and mixing multiple images. 
