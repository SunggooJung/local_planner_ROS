# Source code is going to released soon. (21-06-05)
# local_planner_ROS
Robust Collision-free Lightweight Local Planner for Unknown Area Exploration

### How to build the planner
- Clone the package:
```
git clone https://github.com/SunggoJung/local_planner_ros
```
- Build the package:
```
catkin build -DCMAKE_BUILD_TYPE=ReleaseWidtDebInfo 
```
However, please be aware that the planner requires several dependencies; for example:
- Mapping framework: [Cartographer_ROS](https://google-cartographer-ros.readthedocs.io/en/latest/)
- MAV simulation: Gazebo

### References
If you use this work in your research, please cite the following publication.
```
@article{jung2021robust,
  title={Robust Collision-free Lightweight Local Planner for Unknown Area Exploration},
  author={Jung, Sunggoo and Lee, Hanseob and Shim, David Hyunchul and Agha-mohammadi, Ali-akbar},
  journal={arXiv preprint arXiv:2103.05798},
  year={2021}
}
```

You can contact us for any question:
* [Sunggoo Jung](mailto:sunggoo@etri.re.kr)
