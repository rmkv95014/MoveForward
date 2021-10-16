# MoveForward

## Setup
* Have JDK Installed
* Have WPILib VS Code installed
* Clone this git repo using git clone [url].git
    * If you do not know how to get the [url], click on the green `Code` button
    going to https version (the one that looks like a website link). Copy that link
    and that link will be your [url]

## Complete Robot.java
* Attributes
    * 4 TalonSRX variables 
    * A startTime variable
### Drive5Seconds
* Complete robotInit()
    * Initalize the Joystick variable
    * Initalize all the JoystickButton variables
        * Pass the JoystickButton constructor the JoyStick and a number: either 3 or 4
        (this represents one of the four buttons on the Joystick) 
    * Initalize all the TalonSRX variables
    * Configure them to default settings using `exampleMotor.configFactoryDefault();`
    * Set the follower motors to follow the leaders using `exampleFollower.follow(exampleLeader);`
    * Set the left motors to spin in the opposite direction using `leftSideMotor.setInverted(true);`
* Complete teleopInit()
    * Initalize the startTime variable using the built-in WPILib `Timer` class
    * Check which button has been pressed.
        * Run the motors if the correct button has been pressed.
* Complete teleopPeriodic()
    * Check if five seconds have elapsed, and stop the motors if it has elapsed.
    
### Rotate5Seconds
* Use the same robotInit() method shown above
* Complete teleopInit()
    * Initialize the start time variable using the built-in WPILib `Timer` class
    * Check which button has been clicked
        * If the correct button has been clicked, start the motors
        * This time, you are rotating the robot, not moving it. Adjust the motor speeds accordingly
* Complete teleopPeriodic()
    * Check if five seconds have elapsed, and stop the motors if it has elapsed.


All of the above procedures must follow all JAVA coding conventions. This includes camelCase and 
setting all field variables to be `private`.

Reference the comments in the code for instructions and guidance. You do not need to reference the 
`README.md` for all cases.

**Good Luck!**
