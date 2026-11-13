# M.Tech-Project
In recent years, brushless DC (BLDC) motors have gained significant popularity due
to their high efficiency, reliability, and low maintenance requirements. In traditional
BLDC drives, the rotor position is sensed using Hall-effect sensors, which allow the
windings to be switched at the appropriate times. However, such sensors make the
hardware more complex and expensive, and they also require additional wiring. Sensorless
control, on the other hand, estimates the rotor position and speed from electrical
variables.
A sensorless BLDC motor drive based on a sliding mode observer (SMO) is
proposed in this paper. The observer estimates the back EMF, rotor angle, and
speed. To obtain smooth switching action and reduce the chattering associated with
the traditional signum function, a sigmoid function is used as the nonlinearity in the
SMO. The estimated speed is fed to a PI controller that produces the PWM signal,
while the estimated rotor angle is used in the six-step commutation algorithm, which
generates the gate pulses for the inverter.
The complete control system was implemented in a MATLAB/Simulink model,
and its performance was analyzed using the back EMF, rotor position, rotor speed,
and other related waveforms.
