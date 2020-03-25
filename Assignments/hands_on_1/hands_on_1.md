# Q1
True
# Q2
Overfitting is the term used when a model has been trained so much on a specific data set that when you throw something new at this model it can get confused and has a difficult time giving the correct result
# Q3

A cost function is a way to evaluate the model on how it performs to the actual real results. In many cases its good to use multiple cost functions just to ensure on a few different approaches might evaluate the model.

# Q4

An Epoch is term used to specify how much if the data set has gone through the model. For example 1 Epoch is equal to all the data in the data set has gone through the model 1 time. 50 epochs would be the data has gone through the model 50 times. Based on the video it sounds like typically they see between 50-100 epochs on a model

# Q5

The confusion matrix is another way to assess the performance of an algorithm, but not exactly the accuracy of an algorithm. Its possible that you might have a few cases for a class where it was accurate but overall didnt perform well

# Q6

In the pre-processing stage many frameworks are looking for same size pictures, resolution, format, or color format such as 10-bit. We call this normalization of the images to make sure they are in the same bounds so the algorithms can process the images.

# Q7

Data augmentation was a new term that I have not heard before and it was like a light bulb that went off when I heard it. Its a way take an image and do some image manipulation such as stretch it, flip it, invert it, to give different ways to look at the same data. It sounded like this is a great way to make your model more robust which makes complete sense to be as if all the images were exactly the same orientation I could see overfitting occurring easily. 

# Q8

This is another way to say how well a model is performing. The ranges are between -1 and 1 where 0 means its random chance to getting the right solution. If we have a .7 to .9 that means the model is performing well on its task at the level to almost a human.

# Q9

The equal sampling is a way to ensure that the train data set has equal amount of all classes represented. In real life if we tool a real distribution between the different classes it could be a low amount of data associated to the bad class. Now if we trained the model with this data set we would do really well with the normal class but the bad classes would do poorly in identification. So with equal sampling we make sure that there is around the same number of samples for each class. 
# Q10 - Overfitting?

Yes this is starting to overfit. If we take a look a Loss Overview as you can see around 6 Epochs we are starting to have the validation loss start to go up which is not what we are looking for. A good point to stop training would be around the 6-8 Epochs for the model

# Q11 - Misclassification

If we look at the confusion matrix we would want to look at the boxes that are not on the left to right, top to bottom diagonal as these are the correct identification. So out side of those 4 boxes we want to look at the top 2 boxes that have the highest score. That would be the 797 box and 372 box. The algorithm top misclassification with 797 would be Heterogeneous class where it was really Scattered class. The 2nd top misclassification with 372 was the algorithm identified Scattered where it should have been Heterogenous. 

# Q12
# Q13
# Q14
# Q15
# Q16
# Q17

# Summary