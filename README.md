# SISO

**Theory**

A Serial In Serial Out (SISO) shift register is a sequential logic device that moves data in and out one bit at a time, using a chain of flip-flops connected in series. The primary function is to accept serial data input, shift it across each flip-flop with every clock pulse, and output the data serially from the last flip-flop.​

Construction and Operation
The SISO shift register is made by cascading multiple D flip-flops.

Each flip-flop stores a single bit, and all flip-flops share a common clock signal, ensuring synchronous operation.

Serial input data is applied to the D input of the first flip-flop.

On each clock pulse, the bit stored in each flip-flop moves to the next flip-flop in the chain.

The output of the last flip-flop provides the serial output.

Example
For a 4-bit SISO register and input bits 1011:

Initially, all flip-flops are reset (Q = 0).

On each clock pulse, a new bit enters the first stage, and previous bits move to the next stage.

After four clock pulses, the data is fully shifted through the register, and the last output reflects the last bit shifted in.​

Key Features
Bit Storage: Each flip-flop stores one bit, so a 4-bit register uses four flip-flops.

Timing: Data propagation is controlled by clock pulses; each pulse shifts all bits one stage.

Direction: Data typically shifts left or right, depending on implementation.

Serial Transfer: Only one serial input and one serial output line are used, making it suitable for data transmission and timing applications.​

Applications
Data storage in digital systems.

Time delay implementation.

Data conversion between serial and parallel formats.

Used in counters, signal processing, and digital communication systems.​

