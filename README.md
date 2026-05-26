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

**SERIES RLC CIRCUIT:**

<img width="1610" height="730" alt="image" src="https://github.com/user-attachments/assets/1cdb4195-ad72-4f9e-ae54-c7d28ac16c3f" />

**PARALLEL RLC CIRCUIT:**

<img width="1610" height="661" alt="image" src="https://github.com/user-attachments/assets/f731c436-bdf5-40c4-a087-ddea7754b29b" />

**MODEL GRAPH:**

**SERIES RESONANCE:**

<img width="1352" height="1287" alt="IMG_20260526_145957665" src="https://github.com/user-attachments/assets/1f3f0184-28f1-47a3-852d-b3164cf0902d" />

**PARALLEL RESONANCE:**

<img width="1370" height="1220" alt="IMG_20260526_145948869" src="https://github.com/user-attachments/assets/9bd4bf8e-3596-4c7a-9775-874495921c12" />

**PROCEDURE:**

1.	Construct Series resonance circuit shown on breadboard.
2.	Connect CRO Ch1 to input and Ch2 to output.
3.	Set the input voltage to 4Vp-p.
4.	Vary the frequency from 500Hz to 3 KHz in small steps to get a maximum output voltage magnitude. The frequency at this maximum voltage Vm is the resonance frequency.
5.	If Vcutoff = Vm/√2, vary the frequency again until the output voltage equals Vcutoff. This frequency is the cut-off frequency. There should be 2 cut-off frequencies on either side of resonant frequency.
6.	Calculate the bandwidth by subtracting the 2 cut-off frequencies.
7.	Calculate the Q factor
8.	Repeat steps 1 through 7 for Parallel resonance circuit  shown.

**THEORETICAL CALCULATION:**

<img width="1298" height="948" alt="IMG_20260526_150052218" src="https://github.com/user-attachments/assets/9b23f828-6616-47d8-91d0-0b2263ccbcad" />
<img width="1460" height="1324" alt="IMG_20260526_150103183" src="https://github.com/user-attachments/assets/7c85b297-13c6-47d8-90b6-927eadeace2f" />

**TABULAR COLUMN:**

<img width="2347" height="723" alt="IMG_20260526_150005337" src="https://github.com/user-attachments/assets/ae0be4dd-1218-404f-b23e-d02a6fa08b4b" />

**GRAPH:**

**SERIES RESONANCE:**

<img width="1895" height="381" alt="image" src="https://github.com/user-attachments/assets/4c88ea0e-48e8-4053-b4fe-336f0ede112d" />

**PARALLEL RESONANCE:**

<img width="1895" height="386" alt="image" src="https://github.com/user-attachments/assets/37e794de-d073-4ece-9523-d20662286702" />

**MARKS SPLIT-UP:**

<img width="2932" height="1402" alt="IMG_20260526_150120503" src="https://github.com/user-attachments/assets/82ecc2ec-b2d6-45de-8b28-3169d9450100" />

**RESULT:**

Thus the phenomenon of resonance in RLC circuit was studied and the following were determined using Multisim Simulator.
