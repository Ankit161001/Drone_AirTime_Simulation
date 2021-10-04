# Drone_AirTime_Simulation
Python code for the simulation and graphical representation of data for the comparison of air times between drones which follow two different models.
<h3>Model 1</h3>
The Drone follows a multiple charging station model. When the charge reaches the warning point the drone leaves its assigned zone of surveillance and reaches one among the many available charging stations which is assigned to it by a selection algorithm. 

<h3>Model 2</h3>
The Drone follows a single charging station model. When the charge reaches the warning point the drone leaves its assigned zone of surveillance and reaches the only master charging station. As optimum options are not available, the drone takes more time to move back and forth for charging and its airtime in assigned zone is decreased. 

The airtimes are compared in a graphical manner and the average difference in their airtimes is calculated.
