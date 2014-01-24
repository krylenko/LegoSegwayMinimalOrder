analysis.m -- Matlab file used to model system and calculate min-order observer coefficients
NOTE: requires My_Decouple.m function to decouple state-space system (not include b/c of copyright issues)

controller.c -- code that implements the minimal-order observer on the Lego robot (both controller.c and setup.h are in RobotC)

LegoBalance_no_loop.mdl -- Simulink model of the Lego robot

README.txt -- this file

setup.h -- constants and utility functions for controller.c
NOTE: requires JoystickDriver.c joystick library, included with RobotC, not included in this repo