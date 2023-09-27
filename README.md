Develop a program that when pressing A determinate if it is day or night depending on the light sensor of the microbit by showing a sun icon or a moon icon, and when pressing B determinate if the temperature is cold or warm by showing a flame or a snowflake.
 
The light sensor calculate a value form 0 to 255. 0 meaning no brightness and 255 meaning full brightness.
 
The temperature sensor give us values in Celsius units, which we will have to convert to Fahrenheit units and then consider that anything under 32 is cold and above 32 is warm.
 
C -> F Formula: (Fahrenheit * 9 / 5) + 32

A. When starts we will set the temperature and the light to each sensor value.
B. When A pressed if light sensor is above the 125, show sun symbol.
C. When A pressed if light sensor is below the 125, show moon symbol.
D. When B pressed if temperature sensor in Celsius above 0, show flame symbol.
E. When B pressed if temperature sensor in Celsius below 0, show snowflake symbol.
 
