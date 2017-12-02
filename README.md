# FlaSh9325

Status:

The code can guess the plugboard settings correctly taking into consideration the following:

The known/guessed text must be as good as a sentence(long text)
The known/guessed text must be the starting content of the actual message

Note : These assumptions are made to save some permutations and combination the code has to go through otherwise.

It took almost 3 days time to :

Understand
Analyze
Design the algorithm
Implement

Run as follows:

Encrypt the desired message using enigma.py (Any online simulator with any setting)
Copy the decrypted text into input.txt  ( Note: keep the input.txt file in the same directory as the enigma_Decoder.py)
Copy starting letters of the message ( atleast 15-20 ) of the given desired message 
Run as : python enigma_Decoder.py <copied text>

Improvement :
If possible to change the rotor position to the desired state directly instead of rotating step by step to achieving the same would save thousands for loops
By including functionality to handle any part of the text rather than just the starting part of the desired message




	



