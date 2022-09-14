# Arduino-Project-Music-
ARDUINO PROJECT THAT CREATES TONES OF DIFFERENT FREQUENCIES AND PLAYS IT THROUGH A SPEAKER IN A GIVEN ARDUINO CIRCUIT.

#Steps Involved
* To start out, I will set up the piezo (speaker) on the breadboard of the Arduino on Tinkercad.
* One side of it “the shorter leg side” of the piezo needs to run to ground (GND) through connecting with the terminal 1 of the potentiometer with the negative terminal of the speaker.
* The other side “the longer leg side” needs to connect to a digital output pin.
* A pair of transistors will be connected along this connection.
* Next, I will set up the push button that will link the piezzo with the digital pin 8 directly through its positive terminal.
* Lastly the potentiometers wiper terminal will be connected directly to an input pin which I chose A3.
* The other terminal 2 will be connected to the 5v pin.
* The variation of the frequency of the tone (pitch) with correct timings creates music. The Arduino generates a signal and outputs it through theDigital pin 8.This drives the speaker connected to the pin to create sound.

#The Components used in my Circuit design are as seen in the Screenshot below
![Components Circuit Design](https://user-images.githubusercontent.com/70195777/174504143-180fb606-8fda-46ac-9095-e8a529592ebe.png)

![image](https://user-images.githubusercontent.com/70195777/174504795-41bb1b1c-ff2c-4946-b94f-785c01b6320c.png) #Piezo Speaker
* This are speakers are frequently used to generate sound in digital quartz watches and other electronic devices. Piezo has been used in this project to output sound when the push button is pressed.

![image](https://user-images.githubusercontent.com/70195777/174504868-b5d9c080-8d89-4908-a6eb-c07d6c233a3b.png) #Resistors
* Resistors have been used to limit the amount of current going to certain components in the circuit, such as the push button and the piezo speaker.

![image](https://user-images.githubusercontent.com/70195777/174504909-18d6b397-5a2b-448c-bdd5-ab2f71ce3ab8.png) #Breadboard
* It’s used to build and test circuits quickly before finalizing any circuit design. The breadboard has many holes into which circuit components like push buttons, resistors, potentiometer and jumper wires can be inserted.

![image](https://user-images.githubusercontent.com/70195777/174504943-2ca1bf4f-7de1-44a6-aa4a-4b114ca9c4c7.png) #Push Button
* It’s a component that connects two points in a circuit when you press it. The example turns on the piezo speaker when you press the button.

![image](https://user-images.githubusercontent.com/70195777/174504970-e7a0b9fd-0126-4f35-8de6-d5dcb647aa4a.png) #Potentiometer
* It’s used to vary the pitch of the sound. It calculates the corresponding pitch in the pitch array in order to regulate the sound frequencies produced.

<u> ARDUINO WIRING DIAGRAM TO CONTROL A PIEZO BUZZER WITH A BUTTON </U>
* This Circuit diagram below will display connections all of the components listed previously to the Arduino.
![Arduino Wiring Diagram](https://user-images.githubusercontent.com/70195777/174504339-5de87f1e-9a79-4d79-91f4-a460d8a65693.png)

* When the push button is pressed, the piezo speaker plays sounds at different tones during the simulation.
