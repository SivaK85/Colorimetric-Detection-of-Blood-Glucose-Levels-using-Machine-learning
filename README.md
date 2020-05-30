# Colorimetric-Detection-of-Blood-Glucose-Levels-using-Machine-learning
This is the basic ML  model that I have built from scratch to measure blood glucose levels using accu-chek active strips with visual aid.


The glucose meter is on the table. Patient inserts a new test strip, loads a fresh lancet into the lancing device, snap the tiny needle into the side of patients finger, and squeezes until a fresh, red dome gathers. Then the patient applies the drop of blood to the edge of the strip and waits as the meter counts down to reveal their glucose value


Glucose meters have two essential parts: an enzymatic reaction and a detector. The enzyme portion of the glucose meter is generally packaged in a dehydrated state in a disposable strip or reaction cuvette. Glucose in the patient's blood sample rehydrates and reacts with the enzymes to produce a product that can be detected. 


Some meters generate hydrogen peroxide or an inter-mediary that can react with a dye, resulting in a color change proportional to the concentration of glucose in solution. Other meters incorporate the enzymes into a biosensor that generates an electron that is detected by the meter. There are three principle enzymatic reactions utilized by current glucose meters: glucose oxidase, glucose dehydrogenase, and hexokinase. Each enzyme has characteristic advantages and limitations.


There is a direct correlation between the colour change that takes place after the patient has placed his blood on the test sample and the amount of glucose present in the blood.


In this project I have implemented a glucose measurement technique in which the patient would not require a glucometer but rather would use their smartphone camera. 


The image taken by the smartphone camera would then convert into Cie-LAB value and these values are used to train the model.


The output is a regression value which gives the final glucose value of the patient.


Since Ive been able to gather only few data points to train the model I have created my own custom model to output a value with high accuracy. But this could be made better if more number of input data could be present post which a deep learning model using CNN can be applied.
