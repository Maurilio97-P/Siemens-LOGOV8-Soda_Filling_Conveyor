# Siemens - LOGOV8 - Soda Filling Conveyor Example
This is an example of a Soda Filling Conveyor for LOGO!Soft Comfort V8.2 programmed using Function Block Diagram (FBD).

<p align="center">
  <img src="https://github.com/Maurilio97-P/ABB-RobotStudio-Sorting_Pick-Place/blob/main/Images/sorting.PNG" width="800">
</p>

## Requirements:

**Software:**
```bash
LOGO!Soft Comfort V8.2
```
```bash
CADe_SIMU_4.0
```

| Software/Package      | Link                                                                                  |
| --------------------- | ------------------------------------------------------------------------------------- |
| LOGO!Soft Comfort V8.2 | https://support.industry.siemens.com/cs/document/109767413/logo!-soft-comfort-v8-2-sp1-(download-notes-instructions)?dti=0&lc=en-MX     |
| CADe_SIMU_4.0 | https://github.com/andresWeitzel/CadeSimu3.0  |

## Project Description:
This project is an example of a Soda Filling Conveyor for LOGO!Soft Comfort V8.2 programmed using Function Block Diagram (FBD). It was made by designing the necessary boolean functions for the PLC logic, and by developing the Electrical Diagrams of the **Power Circuit** and the **Control Circuit** for the conveyor. 

The functionality of the conveyor is...


* The **main tools** used to develop this project are:
  * 

## Results:
This simple example was developed to learn the basics of LOGO!Soft Comfort V8.2 and to make all the necessary documentation of the design for the implementation of this project, like the Electrical Diagrams.

You can watch the **video** of the results here:

[<img src="https://github.com/Maurilio97-P/ABB-RobotStudio-Sorting_Pick-Place/blob/main/Images/thumbnail.PNG" width="50%">](https://youtu.be/y0FjnO8AysQ "Tutorial - Pick&Place con RobotStudio de ABB (Proyecto Final)")

https://youtu.be/y0FjnO8AysQ

### The Electrical Diagrams consist of 2 parts:

**Part 1 – Power Circuit**

In this section a .SAT CAD model is imported to generate the gripper in RobotStudio and with Smart Components a sensor is placed on the TCP and the Attach/Detach function is activated with a digital input.

**Part 2 – Control Circuit**

In this section, a conveyor is built by applying physical properties to the belt and to the boxes. Sensors are placed at the end of the conveyor and the belt is stopped if a box is detected at the end.

**Downloading the project (download the .rspag file):**
In case that the UDF block do not show up, verify that the Folder My_UDF_Blocks is linked to the project.

## Contact Info:
maurilio.pp97@gmail.com

## License
[MIT](https://choosealicense.com/licenses/mit/)

