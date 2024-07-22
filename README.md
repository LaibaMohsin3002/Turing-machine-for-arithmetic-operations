# Turing machine for arithmetic operations 
 
The Turing Machine for Arithmetic Operations, developed using C++, performs arithmetic operations including addition, subtraction, multiplication, division, and the function 4x + 5. The Turing machine, a theoretical computational model, consists of a tape divided into cells, a read/write head that moves left or right along the tape, and a set of states that determine the machine's behavior. 

Users can input arithmetic expressions containing these operators along with numerical operands and observe the step-by-step execution of the machine as it processes the input string symbol by symbol. 

In this implementation, each state represents a step in the computation, and each transition rule specifies how the machine should update its state, tape contents, and head position based on the current state and the symbol read from the tape. The provided codes define transition rules for various arithmetic operations, encoded in unary and binary representations, and utilize vectors to store states, transition rules, and tape contents. 
The codes iterate through transition rules for the current state, updating the tape and head position accordingly. If no valid transition is found, it throws a runtime error. Finally, they output the tape contents, head position, and final state.
