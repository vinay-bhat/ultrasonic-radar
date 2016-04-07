This is a DIY cool looking radar using the Arduino Board and the Processing Development Environment.


Requirments:

Hardware: 1.Ultrasonic Sensor(HC-SR-04) (1x) 2.Arduino 3.Breadboard 4.Wires 5.Servo Motor(1x) 6.LED

Software: 1.Arduino IDE(https://www.arduino.cc/en/main/software)
	  2.Processing IDE(https://processing.org/download/?processing)

To build the device 
-- I made a cardboard stand for connecting the Ultrasonic sensor to the Servo motor. I folded it like it’s shown on the picture in bulding device folder glued it and secured to the servo motor using a screw.
-- Also I attached a pin header on which I soldered 4 jumper wires for connecting the sensor.
-- Finally I secured the servo motor to the Arduino Board using glue.


Make the connection as shown in the picture.

Now we need to upload the code to the Arduino Board that will enable the interaction between the Arduino and the Processing IDE. 

We will receive the values for the angle and the distance measured by the sensor from the Arduino Board send it into the Processing IDE using the SerialEvent() function which reads the data from the Serial Port.

Now run the processing code in Processing IDE.