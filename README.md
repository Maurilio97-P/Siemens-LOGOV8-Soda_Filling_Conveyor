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
This project is an example of a Soda Filling Conveyor for LOGO!Soft Comfort V8.2 programmed using Function Block Diagram (FBD). It was made by designing the necessary boolean functions for the PLC logic, and by developing the Electrical Diagrams of the Power Circuit and the Control Circuit for the conveyor. 

The process for filling up the bottles is divided in 2 parts:

**Part I:**

* When pressing start button, the pallet moves to the right as long as it has a bottle. The Motor Starting Method is Direct On-Line Starting (D.O.L.)
* On the way from POINT A to POINT B, the bottle is measured and stops at POINT B to be filled.
  * If the bottle measures 20cm, the filling pump is activated for 10 seconds.
  * If the bottle measures 15cm, the filling pump is activated for 7 seconds.
* Once the bottle is filled, the pallet continues to POINT C and stops the process.
* It is requested to program for a single cycle

**Part II:**

Finish the sequence of Part I and add the following:
* Once at point C, wait for an operator to remove the bottle
* Once the bottle has been withdrawn, the pallet reverses direction and goes to point A
* Upon reaching point A and passing through the Pallet sensor, the process stops and ends.
* It is requested to program for a single cycle

<p align="center">
  <img src="https://github.com/Maurilio97-P/ABB-RobotStudio-Sorting_Pick-Place/blob/main/Images/sorting.PNG" width="800">
</p>

The **main components** used to develop this project are:
  * Function Block Diagram (FBD)
  * User Defined Functions (UDFs)
  * Motor Protection Circuit Breakers (MPCBs)
  * Residual Current Device (RCD)
  * Contactors
  * Thermal Overload Relays
  * 3-Phase Induction Motors

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

**Downloading the project (download the .lsc file):**
In case that the UDF blocks do not show up, verify that the Folder My_UDF_Blocks is linked to the project.

## Contact Info:
maurilio.pp97@gmail.com

## License
[MIT](https://choosealicense.com/licenses/mit/)
