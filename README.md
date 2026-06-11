# 7.FREQUENCY-RESPONSE-OF-SERIES-AND-PARALLEL-RESONANCE-CIRCUITS


**AIM:**

To study the behavior of series and parallel RLC circuits at resonance and to determine the resonant frequency, bandwidth, and Q factor  of the given RLC circuit using Multisim Simulator.

**APPARATUS REQUIRED:**

<img width="504" height="276" alt="image" src="https://github.com/user-attachments/assets/2716f700-2960-4ba2-9e8f-7fa1cebda461" />


**THEORY:**

A resonant circuit, also called a **tuned circuit** consists of L and C. Resonant circuits allow us to select a desired signal from the vast number of signals that are around us at any time. A network is in resonance when the voltage and current are in phase and the network's input impedance is purely resistive. Considering the Parallel RLC circuit, the steady-state admittance offered by the circuit is:
Y = 1/R + j(ωC-1/ωL)
Resonance occurs when the voltage and current at the input terminals are in phase. This corresponds to a purely real admittance, so that the necessary condition is given
by ωC-(1/ωL) = 0
The resonant condition may be achieved by adjusting L,C or ω . Keeping L and C constant, the resonant frequency ω0 is given by:
ω0 = 1/√LC
fo = 1/2π√LC
Frequency Response is a plot of output voltage or current of a resonance circuit as function of frequency. The response reaches a maximum value in the vicinity of the natural resonant frequency, and then drops again to zero as f becomes infinite .The 
 
frequency response is shown in figure 2.The two additional frequencies  f 1 and f 2 are also indicated which are called half power frequencies. These frequencies locate those points on the curve at which the voltage response is 1/√2 or 0.707 times the maximum value. They are used to measure the band-width of the response curve. This is called the half – power bandwidth of the resonant circuit and is defined as:  ΒW =f2 - f1

**CIRCUIT DIAGRAM:**

<img width="1780" height="1335" alt="image" src="https://github.com/user-attachments/assets/039fb0a6-07e5-440c-9a43-acd61607474c" />



**Model graph:**

<img width="1731" height="1299" alt="image" src="https://github.com/user-attachments/assets/445f48f7-9fc3-466e-8c4a-c1e7f723b8f9" />



**TABULATION:**
<img width="1915" height="1436" alt="IMG20260602112443" src="https://github.com/user-attachments/assets/c98a503d-ed98-41ea-84f3-11337f71d2df" />


**Calculation:**

<img width="1519" height="1744" alt="image" src="https://github.com/user-attachments/assets/d05de247-ece8-451b-aa8b-35156175476c" />

**OUTPUT:**

*FOR SERIES RLC CIRCUIT:*
<img width="1916" height="800" alt="image" src="https://github.com/user-attachments/assets/39d41ea5-8615-49cb-b128-476a14abcc8a" />


*FOR PARALLEL RLC CIRCUIT:*
<img width="1916" height="800" alt="image" src="https://github.com/user-attachments/assets/28251eb3-ab56-4124-acc9-22e3981682e7" />


**PROCEDURE:**

1.	Construct Series resonance circuit shown on breadboard.
2.	Connect CRO Ch1 to input and Ch2 to output.
3.	Set the input voltage to 4Vp-p.
4.	Vary the frequency from 500Hz to 3 KHz in small steps to get a maximum output voltage magnitude. The frequency at this maximum voltage Vm is the resonance frequency.
5.	If Vcutoff = Vm/√2, vary the frequency again until the output voltage equals Vcutoff. This frequency is the cut-off frequency. There should be 2 cut-off frequencies on either side of resonant frequency.
6.	Calculate the bandwidth by subtracting the 2 cut-off frequencies.
7.	Calculate the Q factor
8.	Repeat steps 1 through 7 for Parallel resonance circuit  shown.


**RESULT:**

Thus the phenomenon of resonance in RLC circuit was studied and the following were determined using Multisim Simulator.










