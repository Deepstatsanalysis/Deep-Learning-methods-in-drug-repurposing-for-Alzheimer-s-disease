# Deep-Learning-methods-in-drug-repurposing-for-Alzheimer-s-disease

# Overview
Predicting potenial new drugs , which can repurposed for curing Alzheimer's Disease. </br>
We train the model on the pharmacore fingerprints of the Alzheimer's Disease and and </br>
predict potential drugs from the Drug Bank. The model was able to predict 107 new </br>
drug molecules. </br>

Having used a highly imabalanced dataset with 1509 active molecules and 153176 inactive </br>
molecules. We used 80-20 train-test split to validate the performance of the data. And </br>
also because of the class imbalance it is important to find the accuracy of active and </br>
inactive molecules seperately in the Test Dataset. We obtained the best results with </br>
weighted focal loss. </br>

On the **Training Data**-

**precision score**: 0.936 </br>
**recall score**: 0.810 </br>
**f1 score**: 0.868 </br>
**Training accuracy**: 87% </br>

On the **Test Data**-

**precision score**: 0.997 </br>
**recall score**: 0.809 </br>
**f1 score**: 0.893 </br>
**Test accuracy** : 82% </br>
**Active Molecules accuracy** : 77.4% </br>
**Inactive Molecules accuracy** : 81.9% </br>

# Results
Results are also available as tensorboard files in `runs/`

<img src="https://github.com/VIGNESHinZONE/Deep-Learning-methods-in-drug-repurposing-for-Alzheimer-s-disease/blob/master/results/Screenshot%20from%202020-05-04%2011-53-42.jpg" height="500" width="916">
