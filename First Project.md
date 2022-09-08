# First problem statement

Create a classification model to predict whether price range of  mobile based on certain specifications 

# Details of features: 
The columns are described as follows: 
Dataset as 21 features and 2000 entries. The meanings of the features are given  below. 
• battery_power: Total energy a battery can store in one time measured in mAh • blue: Has bluetooth or not 
• clock_speed: speed at which microprocessor executes instructions 
• dual_sim: Has dual sim support or not 
• fc: Front Camera mega pixels 
• four_g: Has 4G or not 
• int_memory: Internal Memory in Gigabytes 
• m_dep: Mobile Depth in cm 
• mobile_wt: Weight of mobile phone 
• n_cores: Number of cores of processor 
• pc: Primary Camera mega pixels
• px_height: Pixel Resolution Height 
• px_width: Pixel Resolution Width 
• ram: Random Access Memory in Mega Bytes 
• sc_h: Screen Height of mobile in cm 
• sc_w: Screen Width of mobile in cm 
• talk_time: longest time that a single battery charge will last when you are • three_g: Has 3G or not 
• touch_screen: Has touch screen or not 
• wifi: Has wifi or not 
• price_range: This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost). 

# Solution presented:
1)Removed handle null values. 
2)Splited data into training and test data. 
3)Applied the following models on the training dataset and generate the predicted value for the test dataset 
a) Logistic Regression 
b) KNN Classification 
c) SVM Classifier with linear and rbf kernel 
4)Predicted the price range for test data 
5)Computed Confusion matrix and classification report for each of these models. 