# Ripple Carry Counter  

This is a **4-bit Ripple Carry Counter** designed and simulated in **Proteus ISIS**. It uses **JK flip-flops** and logic gates to count in binary from 0000 to 1111 (0 to 9).  

## Features  
✅ Uses **JK Flip-Flops (4027 IC)**  
✅ **NE555 Timer** as clock pulse generator  
✅ Displays **4-bit binary output** (A, B, C, D)  
✅ Simple **asynchronous counter** design  

## How It Works  
- The **NE555 timer** generates clock pulses.  
- Each **JK flip-flop toggles** on the falling edge of the previous flip-flop’s output.  
- The final output counts **in binary** and can be seen on logic probes.  

## How to Use  
1. Open the **Proteus** simulation file.  
2. Run the simulation.  
3. Observe the counting sequence on output probes.  
