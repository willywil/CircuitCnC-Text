# CircuitCnC-Text
 Text adventure game for circuits
 -This game is texted based to establish the basic game structure or game engine. Once the game play is functional then i can work to add graphics. 
 -At the start the game should be turn based and similar to the risk board game. once the game play is ready to evolve then I would like the game to 
 -embrace the "real time" aspect of real time strategy game play. 
 -To take a moment and describe real time strategy, you are provided with choices that will allow you to progress to an overall goal. That goal is normally 
 -to conquer the land. To gather resources and use those resources to build and create an empire. If you are faced with an opposition then you need to defend.
 -If your land is threated you attack. 
 -The goal for the game play is too build the circuit that will help you defend an attack or to attack an opponent. Buildings will be able to handle a certain 
 -amount of "energy" applied. Weapons will be the source of energy to apply to buildings. Solder could be a resource to collect as a monitary commodity. 



 Things players can do:
1) Build circuits
	a) The initial build option
		1)Capacitor/Battery is the electron collection facility this is the resources building
		2)Zener diode is a simple voltage regulator device and is useful to build more complex circuits
2) Collect resources (electrons, etc)
3) Build weapons from resources (electrons, etc)
4) Fire those weapons on enemies
4) See instantaneous values that describe the circuit (efficiency, temperature, damage,  resources accumulated)
5) Struggle with events that affect other use cases (like chip shortages)
6) Receive notifications when those events occur

 Things the game needs:
1) Must have a simple ai for game enemies
2) Must have equations to calculate the changing values (distance used as a variable)
3) Matrix used to define the structures and their location on the circuit board
4) immutable variables to define things that will be the same for all players (names of the components, their initial properties, etc)
5) mutable variables used to store information created by the user 
6) Must have Boolean variables to determine whether events like a chip shortage are turned 'on' or 'off'.
7) Must have functions that will change the status of those events
