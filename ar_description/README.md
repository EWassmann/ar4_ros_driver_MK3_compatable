# ar_description

This module contains the hardware description for the AR4 mk3 robot from Annin
Robotics. The URDFs were modified from the original ones but I left the inertial stuff the same,
as well as the origins of parts because I was unsure how they were made 
and wanted any changes if made to be consistent with the way the rest of the values
were found.  The main modifications were to fix some of the joint rotation directions and 
limits and to specify revolute joints. Note that there is a seperate URDF for simulation
which contains the Gazebo plugins.
