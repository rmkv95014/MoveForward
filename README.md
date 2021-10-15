# MoveForward

## Setup
* Have JDK Installed
* Have WPILib VS Code installed
* Clone this git repo using git clone [url].git

## Complete Robot.java
* Attributes
    * 4 TalonSRX variables 
    * A startTime variable
* Complete robotInit()
    * Initalize all the TalonSRX variables
    * Configure them to default settings using `exampleMotor.configFactoryDefault();`
    * Set the follower motors to follow the leaders using `exampleFollower.follow(exampleLeader);`
    * Set the left motors to spin in the opposite direction using `leftSideMotor.setInverted(true);`
* Complete teleopInit()
    * Initalize the startTime variable using the built-in WPILib `Timer` class
    * Start the motors
* Complete teleopPeriodic()
    * Check if five seconds have elapsed, and stop the motors if they have.

All of the above procedures must follow all JAVA coding conventions. This includes camelCase and 
setting all field variables to be `private`.

**Good Luck!**
