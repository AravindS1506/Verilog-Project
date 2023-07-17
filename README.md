# Verilog-Project
This is a basic project to explore various digital circuits on Verilog.
Additionally, a basic traffic light controller was designed.

The traffic light control has 2 lights, highway and farm. A total of four modes: 1) Highway green, farm red 2)Highway yellow, farm red 3)Highway red, farm green 4) Highway red, farm yellow

Assuming the farm has much less traffic compared to the highway, the default mode can be set as green for highway and red for farm. Apart from this we have a three second delay for the yellow modes on both the lights and a ten second delay for the red light on the highway. Due to the higher frequency of vehicles on the highway, the timer is set only for it and not the farm. The farms light is triggered only when a vehicle is detected on the farm via the sensor.

![WhatsApp Image 2023-07-17 at 08 23 48](https://github.com/AravindS1506/Verilog-Project/assets/107163786/9625ee60-678d-41d5-9690-e6fd3bfadf87)
