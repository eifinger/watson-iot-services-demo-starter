Watson IoT Services Demo Starter
====================================

### Watson IoT Services Demo Starter

This repository is the Watson IoT Services Demo Starter which can be deployed into your own repository with a single click.
Just click the button below and start giving hands on demonstrations.

### How does this work?

When you click the button, you are taken to Bluemix where you get a pick a name
for your application at which point the platform takes over, grabs the code from
this repository and gets it deployed.

It will automatically create all needed services and bind them to your app.

It includes a set of default flows that are automatically deployed the first time
Node-RED runs.

#Installation Instructions
1. Click Deploy to Bluemix button.
[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/eifinger/watson-iot-services-demo-starter.git)
2. Login to Bluemix when prompted.
![click_login](https://github.com/eifinger/watson-iot-services-demo-starter/blob/master/documentation/images/click_login.PNG)
3. Accept the automatically generated name or change it.
4. Wait for the orginization and space information to be populated.
5. (Optional) Change the target orginization and space
![accept_defaults](https://github.com/eifinger/watson-iot-services-demo-starter/blob/master/documentation/images/accept_defaults.PNG)
6. Click Deploy
7. Wait for deployment to finish.
![deployment_finished](https://github.com/eifinger/watson-iot-services-demo-starter/blob/master/documentation/images/deployment_finished.PNG)
8. Your App is now deployed. To use all functionalities continue with the next steps.
9. Go to https://console.ng.bluemix.net/dashboard/apps/ and search your newly deployed app.
![new_app](https://github.com/eifinger/watson-iot-services-demo-starter/blob/master/documentation/images/new_app.PNG)
10. Click on your app and wait for it to load. **Do not click on the blue URL.** This will take you directly to the running app, not the admin page.
11. Locate the connections box on the bottom. It should show 5 connected Services.
12. Click on "sample-iot-demo-iotp"
![connections](https://github.com/eifinger/watson-iot-services-demo-starter/blob/master/documentation/images/connections.PNG)
13. Click on "Launch" to launch the Internet of Things Platform Dashboard
![launch_iotp](https://github.com/eifinger/watson-iot-services-demo-starter/blob/master/documentation/images/launch_iotp.PNG)
14. Write down your org id on the top right corner.
![orgId](https://github.com/eifinger/watson-iot-services-demo-starter/blob/master/documentation/images/orgId.PNG)
15. On the left Menu click on Devices and then on the right "Add Device"
![add_device](https://github.com/eifinger/watson-iot-services-demo-starter/blob/master/documentation/images/add_device.PNG)
16. Click on "Create Device Type"
![create_device_type](https://github.com/eifinger/watson-iot-services-demo-starter/blob/master/documentation/images/create_device_type.PNG)
17. Click on "Create Device Type"
![device_type_1](https://github.com/eifinger/watson-iot-services-demo-starter/blob/master/documentation/images/device_type_1.PNG)
18. Set "Watson-IoT-Sensor-Simulator" as the name and leave everything else empty.
![device_type_2](https://github.com/eifinger/watson-iot-services-demo-starter/blob/master/documentation/images/device_type_2.PNG)
19. On the right bottom click "Next" until it says "Create" and click it too.
20. You now have created a Device Type.
![create_device](https://github.com/eifinger/watson-iot-services-demo-starter/blob/master/documentation/images/create_device.PNG)
21. On the right bottom Click "Next" to to create a Device with the new Device Type
22. Name it "Watson-IoT-Sensor-Simulator" and click "Next"
![create_device_1](https://github.com/eifinger/watson-iot-services-demo-starter/blob/master/documentation/images/create_device_1.PNG)
23. Click "Next"
24. On the Security Tab set "Watson-IoT-Sensor-Simulator" as the token and click "Next"
![create_device_2](https://github.com/eifinger/watson-iot-services-demo-starter/blob/master/documentation/images/create_device_2.PNG)
25. Review your Device Information and click "Add"
26. Repeat steps 15-25 with "Watson-IoT-Car-Simulator" for Device Type, Device ID and Device Token to have a separate device for the Car Simulator Use Case
27. You are now ready to play throw the Flow "Temp Sensor with TTS" on your Node RED demo instance
28. Go again to https://console.ng.bluemix.net/dashboard/apps/ to access your app.
