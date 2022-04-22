# oakd_models
URDF models, materials and Gazebo demo worlds for the Luxonis OAKD v1 Stereo AI Camera. 
You will need to run stereo_image_proc along with this model to get disparity images and pointcloud. 

I've validated this model on the Gazebo simulation of my rover, [Tenacity](https://github.com/jetdillo/tenacity_rover), but haven't tested it extensively on other simulations/worlds. \
This replicates the OAKD B&W cameras as described on the [Luxonis Hardware page about the OAK-D](https://docs.luxonis.com/projects/hardware/en/latest/pages/BW1098OAK.html#depth-perception) along with the center RGB camera.
 
You should be able to just drop this into an existing URDF as a xacro macro.
Go check out [Tenacity](https://github.com/jetdillo/tenacity_rover) if you need an example of how to do that. 
If you don't know how to work with XACRO The [ROS Wiki](wiki.ros.org) has a good [tutorial](http://wiki.ros.org/urdf/Tutorials/Using%20Xacro%20to%20Clean%20Up%20a%20URDF%20File) on the subject. 

This is an initial release of this model, so I'm open to feedback, bugs, PRs, etc. 
Thanks,
----Steve " 'dillo" Okay
