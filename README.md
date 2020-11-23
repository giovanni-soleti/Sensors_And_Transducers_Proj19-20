# Sensors_And_Transducers_Proj19-20
In this repository are submitted the code write for the project of Sensors and Transducers. In particular is shown the code flashed on STM-32F446RE Nucleo Board in which a current sensor and rotary encoder has been used with the aim of monitoring torque and control speed of a DC MOTOR. Moreover, is upload a Matlab code in which is shown how is obtained the static characteristic of the motor.

This Repository contain the project of Sensors&Trasducers exam of the Politecnico di Bari, MEng Automation - Robotics.
1.  In LEM-LTA-Analysis there are the Matlab files used to analyze the current measures, there was a parasitic current (at 50 Hz) 
	  which generated measure error. This problem have been solved using a Digital Filter for get a right measure.
2.  In Motor_char the static characteristic of the DC motor (POLOLU 70:1 Metal Gearmotor) has been made applying several load.
3.  In Sensors_and_Trasducers_Proj there is the firmware flashed on STM32F446RE used to get Speed and Current from sensors and the control speed.
