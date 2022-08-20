# SOI_TRYPTICON

#### This git contains:
  - [Source code of arduino](https://github.com/AdumaRishithReddy/SOI_TRYPTICON/blob/main/normal.ino)
  - [Circuit Diagram](https://github.com/AdumaRishithReddy/SOI_TRYPTICON/blob/main/circuit%20(1).png)
  - [Bill of Materials]()
  

### Assembly And Setup
 - We built the chassis following the instructions provided.
- We connected the motor driver to the motors and installed them onto the chassis.
- After that, we connected the Arduino in accordance with the circuit diagram provided [here](https://github.com/AdumaRishithReddy/SOI_TRYPTICON/blob/main/circuit%20(1).png)    
- The following [program](https://github.com/AdumaRishithReddy/SOI_TRYPTICON/blob/main/normal.ino) has been uploaded to the Arduino, allowing it to navigate any maze and avoid obstacles.
-Our model doesn't have to be calibrated.
-The battery must be connected to the Arduino, and if the Arduino were ever to reset, we would need to upload the code from repository to the device.
 
## Structural design
  - Our model was created using two motors and two ultrasonic sensors, and a program was created in accordance. Since we lacked a servo, we used one sensor up front and one on the left. Our model examines the data from both sensors to determine which side of the model is blocked. It then uses this knowledge to determine how to move in a way that avoids running into the obstacles.Our model required the use of a bread board so we arranged it such that it looks like a spoiler to the model.

## Observations
  - We completed our setup and uploaded our primitive code onto the model.
  - Our first observation was that the model was slow and turned really slow,thus we decreased the time and radius of turn by turning the wheels opposite to each other giving it twice the power.
  - Then we noticed that our sensors were sometimes detecting the chassis itself thus we built a holder for the sensor using cardboard.
  - Thereafter, we noticed that our model had a blind spot where it's left wheel gets stuck at an obstacle, thus we put in a block of code avoid such a situation

## References
  - Basic Arduino functions from [Arduino Projects](https://create.arduino.cc/projecthub/saaketporay/ultrasonic-range-finder-9b10b6?ref=search&ref_id=ultrasonic&offset=4)
  - 
