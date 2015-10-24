# KickBOT3
Wooden Steering Robot
//Steering code
//Import necessary classes
import edu.wpi.first.wpilibj.PIDController;
import edu.wpi.first.wpilibj.Joystick;
import edu.wpi.first.wpilibj.PIDOutput;
import edu.wpi.first.wpilibj.PIDSource;
import edu.wpi.first.wpilibj.PowerDistributionPanel;
import edu.wpi.first.wpilibj.SpeedController;
import edu.wpi.first.wpilibj.MotorSafety;
import edu.wpi.first.wpilibj.AnalogPotentiometer;
import edu.wpi.first.wpilibj.IterativeRobot;
import edu.wpi.first.wpilibj.Jaguar;
import edu.wpi.first.wpilibj.smartdashboard.SmartDashboard;
import edu.wpi.first.wpilibj.AnalogPotentiometer;

public class KB3Steering
{

//Pseudo code
//---- Loop ---
//Read POT
//Read joystick angle (do some math here)

//Set your motor speed to the difference between your actual wheel angle and your requested angle (the closer it gets, the //slower it goes)
//Ex: motor.set((requestedAngle-PotValue)*10);
//the *10 at the ends will make sure you don't decelerate too soon, and not reach your angle... you have to adjust this value

//When pot value = requested angle, it will stop automatically
//If value is negative, the difference will also be negative, thus it will move backwards by itself

//--- Loop Back ---

}
