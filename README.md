# Metal-Detector-signal-predicting
Predictive model applied to a metallic soil remediation framework and using inductive detection systems


# Abstract

In this study, we used a predictive model to improve the process of estimating soil pollution and
prioritize metal remediation. We trained the model on simulated and real data to make the compa-
rison as representative as possible. The results showed that the predictive model was effective at
predicting contamination levels of soils based on specific categories of metals, and that the use of
inductive detection systems allowed for similarly precise predictions.
We concluded that our approach could be used to improve metal remediation processes by providing
a precise estimate of contamination levels before beginning the remediation process.
We have thus explored ways to optimize the study of soil in an ecological context to provide a pre-
cise estimate of soil pollution. In this report, you will see the different identification and prediction
techniques used and the ones favored and adapted for our study.

# Clustering prediction (of metal categorie) depending from the frequency 

![image](https://github.com/Adrien-Nicolas/Metal-Detector-signal-predicting/assets/73825898/01f27d6e-6eac-4a6c-86cf-f4ee59185e4a)

On the second graph, we can see the 4 clusters representing the 4 main categories of
permeability. Thanks to this we can add an additional column in the dataset
named "Cluster", representing by 0,1,2 and 3 (non-permeable, ferromagnetic, paramagnetic and
diamagnetic). This will be useful for the next stage of the project, when we want to predict the
main category as a function of frequency and inductance.

# Clustering prediction (of metal categorie) giving by the frequency 

![image](https://github.com/Adrien-Nicolas/Metal-Detector-signal-predicting/assets/73825898/b7bf37c0-2452-4afe-bc3b-cac0f6e0947a)

As you can see above, the prediction is very accurate again, and we can also find all the
different clusters depending this time on the frequency. In red dot we can see the
cluster value for the set frequency value of 45000Hz. We notice that the value
will be placed in cluster 0, which groups together a certain number of values ​​between the values ​​of 40000 and
50000 Hz, which thus remains entirely coherent. According to the values ​​of the dataset, and the clusters generated
recently, this result remains extremely precise. The problem with this method of prediction and
clustering, is that the precision is rather variable depending on the cluster and the permeability values
and other parameters.

# Clustering prediction across multiple dataset, representing multiple land with a lot of metal signal

![image](https://github.com/Adrien-Nicolas/Metal-Detector-signal-predicting/assets/73825898/b5fd2087-f610-4a12-a8db-f916e72979fd)

By carrying out this in-depth study, you will be able to quickly define which are the pre-
sensing the most problematic permeabilities, which will facilitate the decision to prioritize their
pollution. This method thus makes it possible to optimize resources and act in a targeted manner to
address pollution issues.
Within the framework of this simulation, one quickly notices that the terrain concentrating the highest
concentration rate of a metallic category equal to the cluster is the dataset 20. If we observe
that cluster 2 represents a danger to the environment, we will prioritize the depollution of the land
number 20.

# Study

Don't hesitate to read the [ADS_Adrien_NICOLAS.pdf](ADS_Adrien_NICOLAS.pdf) file to have more information about the study. (French version)
