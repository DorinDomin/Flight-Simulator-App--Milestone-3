# -Flight-Simulator-App--Milestone-3
Purpose of this extercise- we created an interface for the operation of an aircraft. Our plain response to instructions from the user regarding the rudder and the variouse control surfaces. The simulartor is desplayed as graphical interface of the cockpit, as shown in the picture below:

## Usage

In order to use the project, you need to do the following steps:

Download FlightSimulator (Or any other simulator) in the next link- https://flightgear.en.uptodown.com/windows. open the simulator, go to Setting, go to Additional Setting and add the next line: "--telnet=socket,in,10,127.0.0.1,5403,tcp --httpd=8080". NOTE! you can choose to use python server. we added a server to this project for your convenience.

In order to log to our programm, a user needs to insert port and ip on the left side of the screen. Note that theres is already an ip and port set by default (they match to the same id and port we inserted the simulator) , that can be changed by typing new ones in the boxes. If communication is formed sucssesfully- a green light will appear and a new flight will be presented on the map using an airplain pin. To set the direction of the plain, the user can use the four control surfaces as decsribed above. The programm know to pin the location of the plain every few second- which gives an exact location.

## Authors
Dorin Domin, Netanel Tamir
