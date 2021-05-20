# UOCIS322 - Project 4 - Ethan Pressley, epressle@uoregon.edu #


## Overview
A brevet time calculator using Flask/AJAX that follows a majority of the ACP guidelines, which includes the below 60km oddity listed in the 'Oddities' section.   
NOTE: This calculator does not cover the 20% longer distance reglulation over the brevet distance.

## Algorithm
This calculator only takes in ACP standard values for the brevet distance (200, 300, 400, 600, 1000). For different control distances, there is a maximum speed and a minimum speed (from control distances 0-1300 km). The maximum speeds strictly decrease, whereas the minimum speeds stay the same, then decrease. These values are used to calculate the opening times and the ending times. A special condition can occur if the first control is below 60km, which prevents the starting point closing before the first control. This special case is covered within the implementation.

## Use
This calculator will automatically update as you insert values into the 'Miles' and 'Km' section.  
This calculator is not intended for negative values.










	
	
	
	




    
	


