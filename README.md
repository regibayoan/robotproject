# robotproject
An autinomous robot car I built for my dissertation
Functions:
1. Self Driving and Self Parking - the robot uses distance sensors to detect distance to objects and therefore performs obstacle avoidance. Sensors are also used to check if there's enough distance between two obstacles for the robot to park in. 
2. Face Recognition - the robot uses camera vision + OpenCV to recognise faces. It was trained to recognise specific faces. This is used as an authentication method for the robot so that the robot will only start if it recognises the face of the person.
3. Bluetooth and WiFi connection - used to take control of the robot as a fail-safe mechanism. Just in case the robot acts up while it's driving autonomously. You can access the robot and perform manual control to prevent damage to the robot.
