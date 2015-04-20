# Elevator

Implement an elevator simulator.

* Elevator can be in one of the states: "going up", "going down", "waiting"
* Elevator delivers passengers to the requested floors
* Elevator accepts requests at any time and schedules them for execution
* After pressing the button, elevator closes doors, and once they are closed, it starts the engine
* Once requested floor is reached, elevator stops the engine and opens the door
* The floors are visited in order
* The direction of the ride does not change until the highest/lowest requested floor is reached
* The elevator can be switched externally to a "maintenance mode" - it goes to the ground floor,
  opens the doors and remains in this state until it's switched back to the "operational mode".
  In the "maintenance mode" the requests are not accepted.
* When there is a power failure (recognized by the engine), the elevator switches itself automatically to the "maintenance mode".