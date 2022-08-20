# SOI_TRYPTICON

#### This git contains:
  - [Source code of arduino](https://github.com/AdumaRishithReddy/SOI_TRYPTICON/blob/main/normal.ino)
  -
  

### Assembly And Setup
  - We built the chassis using the given guidelines.
  - We installed the motors and connected it to the motor driver.
  - We then installed the arduino and connected it according to the circuit diagram given [here]()
  - We have uploaded the following [program]() to the arduino which enables it to avoid obstacles and clear a certain maze.
  - Our model doesn't require any calibration.
  - It requires you to connect the battery to arduino and in a situation where the arduino gets reset we would have to reupload the code onto the arduino
 
## Structural design
  - Our model was designed with 2 motors and 2 ultrasonic sensors and have written a program accordingly. We didn't have a servo thus we used one sensor on the front and one and one on the left. Our model checks both sensors and deduces which side of the model is blocked and proceeds to use this information to move such that it moves without colliding with the obstacles.

## Observations
  - We completed our setup and uploaded our primitive code onto the model.
  - Our first observation was that the model was slow and turned really slow,thus we decreased the time and radius of turn by turning the wheels opposite to each other giving it twice the power.
  - Then we noticed that our sensors were sometimes detecting the chassis itself thus we built a holder for the sensor using cardboard.
  - Thereafter, we noticed that our model had a blind spot where it's left wheel gets stuck at an obstacle, thus we put in a block of code avoid such a situation

## References
  - Basic Arduino functions from [Arduino Projects](https://create.arduino.cc/projecthub/saaketporay/ultrasonic-range-finder-9b10b6?ref=search&ref_id=ultrasonic&offset=4)
