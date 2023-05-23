# Covid-19 Detection using Deep Learning
Developing a deep learning model for automatical detection of Covid-19 phneumonia from frontal chest X-Ray/CT scans. The code was written on Google Colab, so everyone can use the free GPU resources available online to improve the model.

Example Covid-19 and healthy patient chest X-Rays used for training (Note that the healthy examples are pediatric patients) 
![alt text](https://raw.githubusercontent.com/rekalantar/covid19_detector/master/covid_vs_healthy_training.png)

Loss curves 
![alt text](https://raw.githubusercontent.com/rekalantar/covid19_detector/master/loss_curve.png)

Confusion Matrix (accuracy 98%, sensitiviy 93% and specificity 100%)

Correct Healthy Patient Detection (True Negatives):  13\
Incorrect Covid-19 Detection (False Positives):  1\
Incorrect Healthy Patient Detection (False Negatives):  0\
Correct Covid-19 Detection (True Positives):  28\
Total Patietns Diagnosed with Covid-19:  28

![alt text](https://raw.githubusercontent.com/rekalantar/covid19_detector/master/cm.png)

