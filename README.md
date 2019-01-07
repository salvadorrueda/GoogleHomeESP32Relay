# GoogleHomeESP32Relay
Google Home ESP32 Relay using IFTTT and webhooks.

## Getting Started
This project is still in progress and there are a lot of room for improvements but, for now, just works.  

### Parts
* ESP32 with oled display 
* Relay board

### How does it work
Uploading the GoogleHomeESP32Relay code to your ESP32 board you set an HTTP server waiting for an URL that turns on the Relay.
Now you have to make available this server to the Internet by configuring port forwarding to the ESP32 in your router. After that, you can create an IFTTT that uses a certain phrase on Google Assistant to trigger up a webhooks request to the URL that points to your ESP32.

I know this explanation is too short but gives you an idea of who does it work, if you have any question, feel free to contact me. 

