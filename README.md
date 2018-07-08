# Obstacle-detection-using-Ultrasonic-Sensors-on-ESP8266

• We have to figure out the distance because the sensor itself simply holds it's "ECHO"
pin HIGH for a duration of time corresponding to the time it took to receive the reflection (echo) from a
wave it sent.

  • The module sends out a burst of sound waves, at the same time it applies voltage to the echo pin.

  • The module receives the reflection back from the sound waves and removes voltage from the echo
pin.

    • D = 1/2 × T × C
   
Ultrasonic Sensor Connections

• The sensor Vcc is connected to the NodeMCU +3.3v

• The sensor GND is connected to the NodeMCU GND

• The sensor Trigger Pin is connected to the NodeMCU Digital I/O D4

• The sensor Echo Pin is connected to the NodeMCU Digital I/O D3
