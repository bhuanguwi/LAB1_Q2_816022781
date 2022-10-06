# LAB1_Q2_816022781
In question 2, GPIO0 was configured as an outout and GPIO2 was configured as an input
GPIO0 was connected to GPIO2 on the circuit. GPIO0 was toggled on and off in the task.
As a falling edge is seen on GPIO0, the GPIO2 Pin's output is displayed which would also be 0 
as it's input is fed by GPIO0. It was then configured without a falling edge trigger, meaning 
no trigger was used so there was never an interrupt. Therefore, the GPIO2 pin's level was never displayed
as the event queue was always empty.
