# Rain-Prediction-Model

This Github repository will give you full demonstration rain prediction through machine learning, employing a multiple linear regression approach with temperature, humidity, and light intensity as predictive attributes. Ardruino uno interfacing of sensors, including DHT11 for temperature and humidity measurements and LDR for light intensity is done , to gather real-time data for analysis and prediction and model is developed on Raspberry Pi 4.



**Working Principle of DHT11**

DHT11 sensor consists of a capacitive humidity sensing element and a thermistor for sensing temperature. The humidity sensing capacitor has two electrodes with a moisture holding substrate as a dielectric between them. Change in the capacitance value occurs with the change in humidity levels. The IC measure, process this changed resistance values and change them into digital form. For measuring temperature this sensor uses a Negative Temperature coefficient thermistor, which causes a decrease in its resistance value with increase in temperature. To get larger resistance value even for the smallest change in temperature, this sensor is usually made up of semiconductor ceramics or polymers.

**Working Principle of an LDR**

LDR is photoconductivity, which is nothing but an optical phenomenon. When the light is absorbed by the material then the conductivity of the material enhances. When the light falls on the LDR, then the electrons in the valence band of the material are eager to the conduction band. But, the photons in the incident light must have energy superior to the bandgap of the material to make the electrons jump from one band to another band (valance to conduction). Hence, whenlight having ampleenergy, moreelectrons are excited to the conduction band which grades in a large number of charge carriers. When the effect of this process and the flow of the current starts flowing more, the resistance of the device decreases


 
The circuit implemented can be refered as follows:

 <img width="627" alt="image" src="https://github.com/Extremist-18/Rain-Prediction-Model/assets/137435109/69dd5740-b230-4c0d-9ad3-97de89a45b8d">

