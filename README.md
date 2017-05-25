"# Android-Things-Mqtt-DEMO" 

This repo contains demo application for using MQTT on android things via <b>"Eclipse Paho"</b> MQTT client.
In order to use the the project you will require:

<ul>
<li>Android Studio 2.2+
<li>Rasberry-Pi 3 with Android-Things installed.
<li>A bread-board.
<li>2 x jumper wires (female-to-male).
<li>An Led.
</ul>

The following diagram shows configuration:
<br>
<p align="center">
<img src="Android-Things-MQTT-demo.png" width="640px" alt="hardware configuration"/>
</p>
<b>NOTE:</b>
<blockquote> In order to use your own MQTT broker just change the 
<br>
BROKER_URL = "tcp://iot.eclipse.org:1883";
<br>
to 
<br>
BROKER_URL = "tcp://your.broker.url:here";
</blockquote>

