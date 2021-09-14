# Room-Light-Monitoring-Project-Using-Z-Score-Analysis
IoT Practice Project

This project uses BOLT Iot wifi module to detect any anamoly in light source in a room using LDR and ML algorithm which is the Z-score Analysis. It also uses the Twilio API for sending SMS to your phone when ever an anamoly is detected. 

So when you move the light source close to or away from the LDR slowly, the bounds also start changing slowly.
But when you move the light source close to or away from the LDR very fast, the bounds do not change fast enough, and the system detects an anomaly and sends an SMS alert.

Throughout the day, the light in the room will change with the rising and setting of the sun. This change will be slow, and the bounds for the system will change to match this change. But when someone turns on or turns off the lights in the room, the intensity of light in the room will change suddenly. Because of this, the system will detect an anomaly and quickly alert you that someone is in your room.
