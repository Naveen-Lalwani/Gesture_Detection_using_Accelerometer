For this part, I trained a random forest classifier using features like mean, max, 90 percentile and variance of the accelerometer data along the X, Y and Z axis of the android phone's accelerometer to recognize the gestures and recorded a cross validation accuracy of 98%.

The code for the Android App can be found in the <B>AndroidSensorsApp</B> directory. To change the gestures or select different features, make changes in the Model.java file

The gestures chosen were 1, L, N and 2. The <B>trainData.arff </B>file contains the training data recorded for the mentioned gestures and the value of the features.

The <B>1LN2_CrossValidation.png</B> file shows the cross validation accuracy recorded.

The project was done employing Java Weka Library.
