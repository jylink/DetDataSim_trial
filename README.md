# DetDataSim_trial

A drone simulator automatically generates object detection data

Drone mode: auto pilot in the scene and generate object detection data in yolo format

![](https://github.com/jylink/DetDataSim_trial/blob/main/Images/yolo.PNG)

Visible scene

![](https://github.com/jylink/DetDataSim_trial/blob/main/Images/visible.gif)

Night vision

![](https://github.com/jylink/DetDataSim_trial/blob/main/Images/nightvision.gif)


# Usage

This trial version requires Unity 2020.1 and Post Processing Stack v2 

* Download and unzip `DetDataSim_trial.unitypackage`
* `Assets->Import Package->Custom Package...`
* Play in drone mode and collect data under `Screenshots/`


# Playmode

* `Player`: control with WASD and mouse
* `Drone`: auto pilot
* `DroneTracker`: auto pilot, tracking one object a time (for single object tracking task)


# Switch to night vision

1. Disable `Visible` gameobject and enable `NightVision`
2. Check the `Night Vision` in `config`


# Detectable gameobject

Please refer to the two example prefabs in `Prefabs/`
