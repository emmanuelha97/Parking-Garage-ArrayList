# Parking-Garage-ArrayList
Parks and Departs cars in a parking garage
The program will read and process lines of input from a file until end-of-file. Each input line contains a license plate number and an operation (ARRIVE or DEPART), separated by spaces.  Cars arrive and depart in the order specified by the input.  Each input operation must be “echo printed” to an output file, along with an appropriate message showing the status of the operation.

	When a car arrives, the message will include the license number and state whether the car is being parked or turned away because the garage is full.  If the garage is full, the car leaves without ever having entered the garage.
	When a car departs, the message will include the license number and the number of times the car was moved. 

The number of moves does not include the one where the car departs from the garage, or the number of times the car was moved within the garage. It is only the number of times it was moved out of the garage temporarily to allow a car behind it to depart.

If a DEPART operation calls for a car that is not in the garage, the message should so state
