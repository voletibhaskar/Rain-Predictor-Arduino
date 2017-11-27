# Rain-Predictor-Arduino
To predict the probability by analysing the data received from humidity and temperature sensor as well as from LDR .Project find chance of rain on that moment of time.
  # METHODOLOGY
  In this project we have used a sensor module namely DHT11. This module features a humidity and temperature complex with a calibrated digital signal output means DHT11 sensor module is a combined module for sensing humidity and temperature which gives a calibrated digital output signal. DHT11 gives us very precise value of humidity and temperature and ensures high reliability and long term stability. 
	The input from DHT11 and LDR are sensed and the probability of rain is calculated through code, this chance is displayed on LCD display.
  # EXPERIMENTAL STUDY 
This project consists of three sections - one senses the humidity and temperature by using humidity and temperature sensor DHT11. The second section reads the DHT sensor module’s output and extracts temperature and humidity values into a suitable number in percentage
and Celsius scale. And the third part of the system displays humidity and temperature on LCD. Working of this project is based on single wire serial communication. First Arduino send a start signal to DHT module and then DHT gives a response signal containing temperature and humidity data. Arduino collect and extract in two parts one is humidity and second is temperature and then send them to 16x2 LCD.
A liquid crystal display is used for displaying temperature and humidity which is directly connected to arduino in 4-bit mode. Pins of LCD namely RS, EN, D4, D5, D6 and D7 are connected to arduino digital pin number 2, 3, 4, 5, 6 and 7. And a DHT11 sensor module is also connected to digital pin 12 of arduino with a 5k pull-up resistor.
 # RESULT
It is evident from this project work that Temperature and Humidity Sensor Project can be cheaply made from low-cost locally available components and be used to monitor the probability of rainfall at the required place. The designed project was tested a number of times and certified to achieve the aim of the project. This project displays 70% accurate prediction of rainfall. After implementing the LDR to the system the predication of rainfall increases by 4-5%.
