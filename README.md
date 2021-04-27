# Convolution-Neural-Netwotk-Model-VGG16-for-Detection-of-COVID-19-from-Chest-X-Ray-Images

Covid-19 a new severe acute respiratory syndrome coronavirus 2 which has been declared as a pandemic by the WHO and covid-19 exponential infection is a shock to the healthcare systems across the world. Every patient shall to be tested using general techniques like RT-PCR with minimum testing kits may be a huge challenge, and these tests even has an extended turn-around time, and a minimum sensitivity. It is observed that pneumonia can be developed after being infected with Covid-19, which can be examined and detected with the help of a chest x-ray. Considering the fact that having countries with an unstable economy and lack of kits for tests, chest x-rays are the best for the high-risk patients in the quarantine as it is most available in the healthcare systems today than waiting for results from conventional techniques for days. We advise the usage of Chest X-Ray to prioritize the choice of patients for further RT-PCR testing and it might additionally assist in figuring out patients with a excessive chance of COVID with a fake bad end result and wishes to repeat testing. Further, we advise the automatic detection of COVID-19 patients the use of Chest X-Ray snap shots the use of current Deep neural network techniques, in particular in settings in which radiologists aren't available. We present a Convolution neural network-based model (VGG16) to triage patients for suitable testing. On the publicly available covid-chest x-ray-dataset, our model gives 98.7% accuracy for the COVID-19 infection detection.

Datasets:
The dataset used in our work was obtained from the following:
i. Covid X-Ray Image Dataset - https://github.com/ieee8023/covid-chestxray-dataset for positive cases.
ii. Kaggle X-Ray Chest Image-https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia for negative cases.

Dataset	 COVID-19        Healthy    Total number
          images         images          Of
       Train  Test     Train  Test 	   images
 1.	   157     39       157    39	      392

Conclusion and Future work:
Early identification of patients infected with the new coronavirus is critical for selecting the best medication and preventing disease spread. Our findings show that extracting features with CNNs, applying the transfer learning principle, and then classifying these features using unified machine learning methods is an efficient way to classify X-ray images as regular or positive for COVID-19.The imagenet with VGG16 model performed best in Dataset, with a mean acc. of 98.73% and a mean F1-score of 99%.
  The proposed approach has now no longer been examined in humans. As a result, it cannot be used to replace a medical diagnosis since a broader dataset will allow for a more comprehensive investigation. In those circumstances, our research contributes to the development of a reliable, automated, fast, and low-cost method for assisting in the diagnosis of COVID-19 using chest X-ray images.
  In the future, we intend to expand the dataset by adding new X-ray images of COVID-19 patients as soon as they become available, as well as X-ray exams of other lung-related diseases, thus confirming the efficiency of the proposed method. Furthermore, we want to put the proposed approach to the test on an unbalanced dataset.
