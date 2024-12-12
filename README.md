### Name : MADHUPRIYA R
### Register No : 24900083
# EXPERIMENT NO 6 : SR FLIP FLOP 

*AIM:*

To implement  SR flipflop using verilog and validating their functionality using their functional tables.

*SOFTWARE REQUIRED:*

Quartus prime


*THEORY*

SR Flip-Flop SR flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, SR latch operates with enable signal. The circuit diagram of SR flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/0f710028-ad52-4d3e-9276-8714cf023a25)

 
This circuit has two inputs S & R and two outputs Qtt & Qtt’. The operation of SR flipflop is similar to SR Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of SR flip-flop.

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/dabfc4f4-87e3-4cbc-9472-f89ee1b5ed30)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, SR flip-flop can be used for one of these three functions such as Hold, Reset & Set based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of SR flip-flop. Present Inputs Present State Next State

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/dd90d16c-aec5-4290-a586-e2346b1e9eb5)

 
By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. The three variable K-Map for next state, Qt+1t+1 is shown in the following figure.

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/473efad6-d70b-4ca7-aeb7-898bbfca319f)

 
The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=S+R′Q(t)Q(t+1)=S+R′Q(t)

*PROCEDURE*

Implementing SERIAL-IN-SERIAL-OUT-SHIFTREGISTER functions in Verilog HDL (Hardware Description Language) involves translating the simplified Boolean expressions into Verilog code to describe the behavior of digital circuits. The basic building blocks in Verilog is module. The module represent a combinational circuit. Use logical operators (&, |, ~, ^) to implement Boolean functions directly. Use built-in gate primitives for basic functions. Use University program VWF to verify the functionality of your Verilog modules. Create waveform and check outputs against expected results

*PROGRAM*

![Screenshot 2024-12-12 132807](https://github.com/user-attachments/assets/bfbd7ba0-ec5d-4c6f-9dae-be5558186e33)


*RTL LOGIC FOR FLIPFLOPS*


![Screenshot 2024-12-12 132322](https://github.com/user-attachments/assets/a2b3f0db-2a75-47df-89c7-2ee98b147064)

*TIMING DIAGRAMS FOR FLIP FLOPS*

![Waveform](https://github.com/user-attachments/assets/15c71ee0-278d-4054-90e6-c39b680903e5)

*RESULT*

Successfully implemented  SR flipflop using verilog and validating their functionality using their functional tables.
