# mav_with_rgbd_camera
  rotors equiped realsense d435i, outputs color depth pointcloud .

Welcome to the mav_with_rgbd_camera wiki!

TO start: 

```
mkdir -p ~/catkin_ws/src
cd ~/catkin_ws/src
git clone https://github.com/9woods123/mav_with_rgbd_camera.git
cd ..
catkin_make
source devel/setup.bash
```

To run a simple example, run 

`roslaunch rotors_gazebo mav_hovering_example_with_realsense.launch 
`


![2023-02-20 17-11-23 的屏幕截图](https://user-images.githubusercontent.com/78521063/220062401-fed03690-09df-4d68-99eb-ab9654b8289b.png)
