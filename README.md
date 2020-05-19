# DJ_Portfolio
Data science portfolio

# [Project 1: Titanic survival classification problem](https://www.kaggle.com/dejunhuang/getting-started-with-titanic)
* Step through the use of Kaggle kernals and result subimission
* Perform exploratory data analysis (EDA) on the dataset
![](https://github.com/djhuangit/DJ_Portfolio/blob/master/images/hist.png)
* Use basic (fixed value) and advanced methods (calculated values from different slices of data) for fillna
![](https://github.com/djhuangit/DJ_Portfolio/blob/master/images/p1_fillna.JPG)
* Compared some of the most widly used classifiers in practice (Randomforest, gradientboosting, xgboost)
* Use early stop & slow learning rate strategy to get close to the global minima


# [Project 2: Laser-metal spatter classification with SciKit-learn and Pytorch](https://github.com/djhuangit/spatter_img_classifier)
* Collect spatter images using object tracking algorithms with semi-auto labelling (good vs bad)
* Explore differerent image binarization technqiues
* Use CNN constructed by Pytorch to train a classifier
* Compare CNN model performance trained with RGB, grayscale and binary images
* Remove the last softmax layer and convert features residing in the 2nd-last layer to a score for similarity check 
* Use clustering method from SciKit-learn to learn the decision hyperplane between two classes, and convert the distances from the decision plane to scores for similiarity check
* Use existing template matching method for similarity check
