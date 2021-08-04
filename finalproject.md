## Title
Predicting the Potability of Water
## Abstract (Problem Statement)
Potable water is water that is fit or suitable for drinking. The benefits of drinking potable water include increasing energy, reducing fatigue, supporting weight loss, removing toxins from the body, and assisting in the digestion of food and prevention of constipation. On the other hand, drinking contaminated water can cause people to have diarrhea, stomach cramps, vomiting, and pneumonia. If you drink water with contaminants like arsenic, you can increase your chance of developing cancer. Although water treatment methods like boiling water for at least an hour, filtering water through ceramic filters, and filtering water through simple carbon-activated filters can remove many contaminants from tainted water, they cannot take out all the contaminants from the water. However, I plan to use the features of potable water such as pH, capacity of water to precipitate soap in mg/L, total dissolved solids in ppm, amount of Chloramines in ppm, amount of Sulfates dissolved in mg/L, conductivity, amount of organic carbon in ppm, amount of Trihalomethanes in μg/L, turbidity in making a model to predict potability. To make this model have a higher chance of accurately predicting potability, I plan to experiment with different combinations of these numerical features in the model. If I can figure out what combination of features helps increase the model’s accuracy, I could find out the features necessary to differentiate between contaminated and potable water. In addition, this discovery could lead to a way to perfectly converted contaminated water into potable water.
## Description of Data
-Source of Data: Kaggle --> [here](https://www.kaggle.com/adityakadiwal/water-potability)

-Continuous Features: 

+ pH

+ Hardness
  
+ Solids
  
+ Chloramines
  
+ Sulfate
  
+ Conductivity
  
+ Organic Carbon
  
+ Trihalomethanes
  
+ Turbidity 

-Discrete Target: Potability (specifies if water is safe for human use or not & uses values 0 and 1, 1 means that water sample is potable, 0 means that water sample is not potable)

-Description of Dataset Size: 3276 rows / observations x 10 columns (9 features / variables + 1 target)

-(After using dropna method to remove null values from the dataset) Description of Dataset Size: 2011 rows / observations x 10 columns (9 features / variables + 1 target)

-Source: The data was collected from 3276 different water bodies.


