## Title
Predicting the Potability of Water
## Abstract 
Potable water is water that is fit or suitable for drinking. The benefits of drinking potable water include increasing energy, reducing fatigue, supporting weight loss, removing toxins from the body, and assisting in the digestion of food and prevention of constipation. On the other hand, drinking contaminated water can cause people to have diarrhea, stomach cramps, vomiting, and pneumonia. If you drink water with contaminants like arsenic, you can increase your chance of developing cancer. Although water treatment methods like boiling water for at least an hour, filtering water through ceramic filters, and filtering water through simple carbon-activated filters can remove many contaminants from tainted water, they cannot take out all the contaminants from the water. However, I plan to use the features of potable water such as pH, capacity of water to precipitate soap in mg/L, total dissolved solids in ppm, amount of Chloramines in ppm, amount of Sulfates dissolved in mg/L, conductivity, amount of organic carbon in ppm, amount of Trihalomethanes in μg/L, turbidity in making a model to predict potability. To make this model have a higher chance of accurately predicting potability, I plan to experiment with different combinations of these numerical features in the model. If I can figure out what combination of features helps increase the model’s accuracy, I could find out the features necessary to differentiate between contaminated and potable water. In addition, this discovery could lead to a way to perfectly converted contaminated water into potable water.

## Problem Statement

## Description of Data
-Source of Data: Kaggle --> [here](https://www.kaggle.com/adityakadiwal/water-potability)

-Continuous Features: 

+ pH (It is a measure used in determining the acid-base balance of water & indicating. The World Health Organization says that for most safe drinking water the pH values should range from 6.5 to 8.5. Generally, lower pH values are correlated with higher potential levels of corrosion.)


+ Hardness (It is the water's ability to precipitate soap and is usually a result of calcium and magnesium. Usually, the hardness for safe drinking water should not exceed 120 to 170 mg/L.)
  

+ Solids (This measure of water is also known as Total dissolved solids or TDS. 500 ppm of TDS usually should be the maximum amount of one's drinking water. However, any water sample exceeding 1000 ppm of TDS is unsafe.)
  

+ Chloramines (Chloramines are disinfectants involved in treating drinking water and in public water systems. According to Centers for Disease Control and Prevention, water samples containing chloramine levels up to 4 ppm are considered safe. Drinking small quantities of chloramine does not lead to harmful health effects and protects against waterborne disease outbreaks.)
  

+ Sulfate (Sulfates are natural substances located in minerals, soil, rocks, ambient air, groundwater, plants, and food. They are mainly used in the chemical industry. Water samples with 250 mg/L of sulfates should ensure that humans drinking the water will avoid the esthetic effects of sulfate. In addition, water samples should not go beyond 500 mg/L of sulfates to avoid the laxative effects of sulfates.)
  

+ Conductivity (Electrical conductivity is a measure of the ionic process of a solution that allows it to transmit a current. Conductivity and TDS seem to be related due to the quantity of dissolved solids in water usually determining the electrical conductivity. The World Health Organization states that Electrical Conductivity values in safe water samples should not be larger than 400 μS/cm.)
  

+ Organic Carbon (Total Organic Carbon measures how much carbon is in organic compounds in pure water. Usually, Total Organic Carbon values in safe drinking water go up to 25 ppm.)
  

+ Trihalomethanes (Trihalomethanes are chemicals that can be located in water treated with chlorine. Water samples with trihalomethane levels below or around 80 ppm or 80000 μg/L are considered safe for drinking.)
  

+ Turbidity (Turbidity is used to measure light emitting properties of water and is related to the quantity of solid matter present in water. The units used in this measurment is Nephelometric Turbidity Units. For safe drinking water, turbidity values should be lower than 5 NTU.)


-Discrete Target: Potability (This target specifies if water is safe for human use or not & uses values 0 and 1. 1 means that water sample is potable. 0 means that water sample is not potable)

-Description of Dataset Size: 3276 rows / observations x 10 columns (9 features / variables + 1 target)

-(After using dropna method to remove null values from the dataset) Description of Dataset Size: 2011 rows / observations x 10 columns (9 features / variables + 1 target)

-Source: The data was collected from 3276 different water bodies.

+ However, potable ranges in the dataset differ some from the general safety measures of potable water. For potable water of this dataset, pH values range from 0.2275 - 11.8981. Hardness values range from 73.4922 to 317.3381 mg/L. Values of Total dissolved solids range 1198.9437 to 56488.6724 ppm. Values of Chloramines range from 1.3903 to 13.127 ppm. Sulfate values range from 129 to 481.0306 mg/L. Conductivity values range from 201.6197 to 695.3695 μS/cm. Organic Carbon values range from 2.2 to 23.6043 ppm. Trihalomethanes values range from 8.577 to 124 μg/L. Turbidity valeus range from 1.45 to 6.4947 NTU.   

+ 
