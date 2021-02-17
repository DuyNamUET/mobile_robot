# Mobile Robot Simulation using MATLAB Simulink
MATLAB version: 2016a <br>
The note about equation and theory was represented in [RoboticsVisionAndControl](https://github.com/DuyNamUET/RoboticsVisionAndControl) (Chapter 4)

## Files Structure
+-- params_bicycle.m: *The parameters of Mobile Robot type Bicycle* <br>
+-- params_quadrotor.m: *The parameters of Quadrotor* <br>
+-- quadrotor_dynamics.m: *The dynamic of Quadrotor* <br>
+-- quadrotor_plot.m  *The file that using for plot Quadrotor in 3D*
+-- sml_bicycles.slx: *The Simulink file represent the Mobile Robot type Bicycle model* <br>
+-- sml_driveline.slx: *The Simulink file represent the model drive Mobile Robot followed the line based on Bicycle model* <br>
+-- sml_drivepose.slx: *The Simulink file represent the model drive Mobile Robot to a pose (x, y, theta) based on Bicycle model* <br>
+-- sml_movepoint.slx: *The Simulink file represent the model drive Mobile Robot to a point (x, y) based on Bicycle model* <br>
+-- sml_quadrotor.slx: *The Simulink file represent the Quadrotor model* <br>
+-- sml_trajectory.slx: *The Simulink file represent the model drive Mobile Robot followed the defined trajectory based on Bicycle model* <br>
+-- sml_unicycle.slx: *The Simulink file represent the Unicycle model*