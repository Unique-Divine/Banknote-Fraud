# Banknote Fraud Classification - Decision Tree from Scratch
## Summary: ##
The goal of this project was to get practice writing a decision tree from scratch. I figured that this could serve as an effective technical exercise.
 
## **Data Description**:
Extracted from images were taken from genuine and forged banknote-like specimens. For digitization, an industrial camera usually used for print inspection was used. The final images have 400x 400 pixels. Due to the object lens and distance to the investigated object gray-scale pictures with a resolution of about 660 dpi were gained. Wavelet Transform tool were used to extract features from images.

**Dataset Attributes**:
1. variance of Wavelet Transformed image (continuous)
2. skewness of Wavelet Transformed image (continuous)
3. curtosis of Wavelet Transformed image (continuous)
4. entropy of image (continuous)
5. class (integer)

## Next Step / To-Do:
* The decision tree is done, but I'd like to try to implement a random forest using the decision tree class. 
* Afterward, I'll turn this entire repo into a tutorial, so people won't have to struggle as much as I did to understand some of the concepts involved writing a random forest algorithm.   
