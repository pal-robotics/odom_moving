odom_moving
===========

Two services to move straight and rotate via odometry publishing on a cmd_vel topic

It does not have any safety measure.
On the REEM robots another layer offers this security.

Use as:
rosservice call /turn_nav "enable: true degrees: 45.0" 
Will rotate 45 degrees clockwise.

rosservice call /straight_nav "enable: true meters: -0.3" 
Will move backwards 0.3 meters.

