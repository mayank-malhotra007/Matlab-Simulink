# Stateflow

Stateflow is a matlab-simulink toolbox designed to model and simulate state machines and flow charts graphically.
- create finite state machines, control logic, event driven systems
- build states, transitions between states, actions, events 
- model complex logic, like mode switches, safety controllers, protocols, user interfaces
- integrates with simulink
- is visual and intuitive 
- generate code for embedded systems



## Components




### Function Call Generator
A FCG is a simulink block that perdiodically produces a function call event signal not a regular numeric signal.
A normal signal is value over time, like voltage or speed.
A function call event is like a trigger pulse, like a button press or an intertupt. Events in Simulink will require a function call event not a normal signal.






