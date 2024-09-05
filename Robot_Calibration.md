
# Robot Calibration (On Teach Pandant)
## Check robot calibration data from teach pandant
* Click [ROBOT] on left menu, and select [ROBOT CALIB]

<img src="images/robotcalibration01.png" alt="Alt Text" width="300" height="auto">

* Click [DISPLAY] and select [COORDINATE DATA]

<img src="images/robotcalibration02.png" alt="Alt Text" width="300" height="auto">

<img src="images/robotcalibration03.png" alt="Alt Text" width="300" height="auto">

* The data shown on the screen will be robot calibrated configuration:

<img src="images/robotcalibration04.png" alt="Alt Text" width="300" height="auto">

## Robot calibration
* Use [select] on teach pandant and select the robot group to calibrate:

<img src="images/robotcalibration05.png" alt="Alt Text" width="300" height="auto">

<img src="images/robotcalibration06.png" alt="Alt Text" width="150" height="auto">

* Use `5 points rule` for calibration:
Point the TCP of robot#1 to a reference point on robot#2, and keep them pointing each other for all 5 points:

<img src="images/robotcalibration07.png" alt="Alt Text" width="300" height="auto">

<img src="images/robotcalibration08.png" alt="Alt Text" width="150" height="auto">

Jog C1, C2, C3 with fixing 2nd axis of robot#2.
Jog C3, C4, C5 with fixing 1st axis of robot#2.
Use [MODIFY] + [ENTER] to adjust C1 - C5.

<img src="images/robotcalibration09.png" alt="Alt Text" width="300" height="auto">

Click [COMPLETE] to finish robot calibration, if errors happen, follow the error instruction to re-adjust C1 - C5.

<img src="images/robotcalibration10.png" alt="Alt Text" width="300" height="auto">
