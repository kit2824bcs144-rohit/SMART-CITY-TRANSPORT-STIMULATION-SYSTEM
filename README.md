🔧 Functions Description
1. calculateFare(double distance)

Purpose: Calculates the travel fare based on distance.

Type: Virtual function (overridden in derived classes).

Description:
Each transport mode (Metro, Bus, Taxi) has its own fare calculation logic.
This demonstrates polymorphism.

2. display()

Purpose: Displays the selected transport mode.

Type: Virtual function.

Description:
Prints the name of the transport chosen by the user (Metro/Bus/Taxi).

3. saveToFile(string mode, double distance, double fare)

Purpose: Stores trip details permanently.

Description:
Saves transport mode, distance traveled, and calculated fare into a text file (transport_log.txt) using file handling.

4. main()

Purpose: Entry point of the program.

Description:

Accepts user input (transport type and distance)

Creates appropriate transport object

Calls fare calculation

Displays output

Saves trip details to file
