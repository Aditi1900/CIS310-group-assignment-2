# CIS310-group-assignment-2 Documentation

Register File Design: the write data was implemented by using a demultiplexer and having a 2-bit control "Select_Write" with an 4-bit input "Write_data", this demultiplexer had 4 different output pins allowing us to control what register we write to. The two independent read ports used multiplexers to select which register it will read from. both the read ports have their own 2-bit control "Select_read1" and "Select_read2".Both of this control inputs lets us read 2 different registers.


ALU Implementation: For the ALU implementation, we used a 4-bit adder to handle addition and subtraction, utilizing bitwise complementing of B and conditional addition of 1 for subtraction operations. Increment and decrement operations were achieved by feeding A into the adder with fixed inputs (0001 for increment and 1111 for decrement). Transfer operations were handled using multiplexers to pass A directly to the output. The control signals ({S1, S0, Cin}) determined the selection of operations as per the provided table. 

Testing: Show input/output waveforms or screenshots demonstrating each operation.



Register File test:
![image](https://github.com/user-attachments/assets/0664453a-5abb-4631-88ad-4ec70c31ca7f)
Test shows that values are correctly written.

