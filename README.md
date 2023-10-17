# Finite-State-Machines

A finite state machine is a computational model for a machine that is *always in a fixed state*. Each finite state machine has a finite number of states and can only ever be in one state at a point in time.

The state of a finiter state machine will change depending on the current state and the input data. If the input data is valid, the finite state machine will terminate in an accepting state.

A finite state machine's state can change and does so according to transition rules, rules that describe what a finite state machine should do given certain criteria. 

State transition diagrams are used by computer scientists as a visual representation of a 
finite state machine. They consist of states (circles) joined by transitions (arrows) and 
always have a start state, indicated with a leading arrow. An accepting state is shown as a 
double circle. 

![image](https://github.com/Minwauu/Finite-State-Machines/assets/110039102/41eb2d37-72ac-4c25-b611-915fdfd020da)

For example, the state transition diagram above has four states: S0
, S1
, S2
 and S3
. The 
start state is S0
 and S3
 is an accepting state. 
The transition functions are each represented by an arrow (the leading arrow merely 
signifies the start state and does not represent a transition function). 
The finite state machine represented by the state transition diagram will only accept input 
data that starts with 11​. For example: 11​, 110​, 11101​ and 11001100. 
