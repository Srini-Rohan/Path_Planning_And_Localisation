# Path Planning And Localisation
#### For Gmapping
```bash
roslaunch nav gmapping.launch 
rosrun map_server map_server map.yaml  #To save the map
```
#### For localisation
```bash
roslaunch nav amcl.launch 
```
#### For Path Planning
```bash
roslaunch nav move_base.launch 
```
