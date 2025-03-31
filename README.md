# CIS310-group-assignment-2 Documentation

Register File Design: the write data was implemented by using a demultiplexer and having a 2-bit control "Select_Write" with an 4-bit input "Write_data", this demultiplexer had 4 different output pins allowing us to control what register we write to. The two independent read ports used multiplexers to select which register it will read from. both the read ports have their own 2-bit control "Select_read1" and "Select_read2".Both of this control inputs lets us read 2 different registers.


ALU Implementation: How you handled add, subtract, increment, decrement, and transfer operations.

Testing: Show input/output waveforms or screenshots demonstrating each operation.
