# Test Case #1:

## Input:
| PID 	| Priority 	| Arrival Time 	| Burst Time 	|
|-----	|----------	|--------------	|------------	|
| 1   	| 1        	| 2            	| 3          	|
| 2   	| 4        	| 5            	| 6          	|
| 3   	| 0        	| 8            	| 9          	|
| 4   	| 1        	| 2            	| 3          	|
| 5   	| 4        	| 2            	| 6          	|

Enter Time Quantum(Multiples Of two):2 <br>
<img src =Screenshots/2.Enter%20Input.PNG width="650" height="350" alt="Input Processes">

## Output:

| PID 	| Priority 	| Arrival Time 	| Burst Time 	| Completion Time 	| TurnAround Time 	| Waiting Time 	| Response Time 	|
|-----	|----------	|--------------	|------------	|-----------------	|-----------------	|--------------	|---------------	|
| 1   	| 1        	| 2            	| 3          	| 5               	| 3               	| 0            	| 2             	|
| 2   	| 4        	| 5            	| 6          	| 29              	| 24              	| 18           	| 19            	|
| 3   	| 0        	| 8            	| 9          	| 17              	| 9               	| 0            	| 8             	|
| 4   	| 1        	| 2            	| 3          	| 8               	| 6               	| 3            	| 5             	|
| 5   	| 4        	| 2            	| 6          	| 27              	| 25              	| 19           	| 17            	|

All Processes Completed In 29 unit time.<br>
<img src =Screenshots/3.Output.PNG width="650" height="350" alt="Output">

## Status: 
### Passed
### You Are Free To find bugs
