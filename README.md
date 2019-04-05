# SLAM
**Simultaneous Localization and Mapping**



Simultaneous localization and mapping using a graphing method is implemented here using Kalman filters.

Localization and mapping for the final project was done on a 2-dimensional world. For localization and mapping a two step approach was utilized

- A function was written to determine if landmarks were accessible to the robot sensing capabilities or not ( these sensing capabilities would be equipments like LIDAR, IR, ultrasound frequencies, radio frequencies etc)

- An update function was written that takes in all the time step measures for every "sensable" landmark and also the motion measurement and then updates the position of the landmarks 

