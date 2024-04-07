# SleepBalanceLiteratureReview

Over the course of the semester, we transcribed data from 29 articles regarding the effects of sleep on various actvity variables on older adults. (See Literature_Review_ALP.xlsx for full transcription) 

After transcribing data from 29 articles, we converted the data into binary data indicating whether a sensor was included in a sleep monitoring device and whether a sleep outcome variable was measured

**Goal**
To determine whether a device having a specific sensor is indicative of a sleep outcome variable being measured.


93.5% articles use sleep monitoring devices with an acceleration sensor, 29% with an ultraviolet sensor, 22.5% with a temperature sensor, and 48% with a heart rate sensor.

We found that there is not enough evidence to conclude that any of these sensors have a significant effect on the number of sleep outcomes measured. 

We then performed the regression for each sleep variable (TST, SOL, SE, etc.) individually. 

For most of the sleep outcome variables, the coefficients in the model were statistically significant. However, for DST, LST, Awake time and SOL, the presence of a heart rate sensor is a significant indicator of these sleep outcome variables being measured. Additionally, for sleep efficiency, the presence of an ultraviolet sensor is also a significant indicator of the sleep outcome variable being included in the article. This suggests that these sensors may play a role in monitoring and predicting these aspects of sleep quality and duration.

![image](https://github.com/andreac0ntreras/SleepBalanceLiteratureReview/assets/64513150/c5aeee59-04d1-4443-ae84-f897f9b73b31)


To view the full statistical analysis, open the ![RMD File](https://github.com/andreac0ntreras/SleepBalanceLiteratureReview/blob/main/Sleep%20and%20Balance.Rmd) with R Studio and run all. 

