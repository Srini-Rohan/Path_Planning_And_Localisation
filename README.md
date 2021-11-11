# Path Planning And Localisation
#### For Gmapping
```
roslaunch nav gmapping.launch 
rosrun map_server map_server map.yaml  #To save the map

```
#### For localisation
```
roslaunch nav amcl.launch 

```
#### For Path Planning
```
roslaunch nav move_base.launch 

```
