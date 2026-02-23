## Experiment No: 2
## NON-INVERTING AMPLIFIER USING OP-AMP (μA741)
## Aim
To design and simulate a Non-Inverting Amplifier using μA741 in Proteus Design Suite and verify its voltage gain.
## Apparatus Required
•	μA741 Op-Amp
•	Resistor R1 = 10 kΩ
•	Resistor Rf = 100 kΩ
•	Signal Generator (1 kHz sine wave)
•	Dual Power Supply (±15V)
•	CRO / Oscilloscope
•	Connecting wires
## Circuit Diagram

<img width="940" height="545" alt="image" src="https://github.com/user-attachments/assets/46516e31-c1d6-4674-8c55-0c00c315aeff" />

Pin Configuration:
•	Pin 3 → Input (Non-inverting)
•	Pin 2 → Feedback network
•	Pin 6 → Output
•	Pin 7 → +15V
•	Pin 4 → −15V
## Theory
A Non-Inverting Amplifier is a closed-loop amplifier configuration in which the input is applied to the non-inverting terminal (+) of the op-amp.
The output signal is amplified and remains in phase with the input signal.
## Procedure
1.	Open Proteus software.
2.	Select μA741, resistors, signal generator, and CRO.
3.	Connect circuit in non-inverting configuration.
4.	Set R1 = 10kΩ and Rf = 100kΩ.
5.	Apply ±15V supply.
6.	Give input sine wave of 1V, 1kHz.
7.	Run simulation.
8.	Observe input and output waveforms.
## Waveform
<img width="940" height="597" alt="image" src="https://github.com/user-attachments/assets/6c11997a-f2a1-44af-839a-1fde6770cf11" />

## Tabulation

| Sl. No | Input Voltage (Vin) | Output Voltage (Vout = 11Vin) |
| ------ | ------------------- | ----------------------------- |
| 1      | +0.1 V              | +1.1 V                        |
| 2      | +0.2 V              | +2.2 V                        |
| 3      | +0.5 V              | +5.5 V                        |
| 4      | 0 V                 | 0 V                           |
| 5      | –0.1 V              | –1.1 V                        |
| 6      | –0.2 V              | –2.2 V                        |
| 7      | –0.5 V              | –5.5 V                        |

## Result
The Non-Inverting Amplifier using μA741 Op-Amp was designed and simulated successfully.
The voltage gain obtained is approximately 11.
The output waveform is in phase with the input waveform.
## Conclusion
•	Gain depends on resistor ratio (Rf/R1).
•	Output is amplified without phase reversal.
•	Practical values are close to theoretical values.
## Viva Questions
1.	What is a Non-Inverting Amplifier?
2.	What is the gain formula?
3.	Why is output in phase?
4.	What happens if Rf increases?
5.	What is the input impedance of non-inverting amplifier?

ANSWER:

1. **Non-Inverting Amplifier:**
  An op-amp circuit where the input signal is applied to the positive (+) terminal. The output voltage is amplified without changing the signal polarity.

2. **Gain Formula:**
    Voltage gain,It depends on the feedback resistor ( R_f ) and input resistor ( R_1 ).

3. **Why output is in phase:**
    The input is given to the non-inverting (+) terminal, so the op-amp amplifies without phase reversal. Hence output and input have 0° phase difference.

4. **If ( R_f ) increases:**
   The voltage gain increases because gain is directly proportional to ( R_f ). So output amplitude becomes larger.

5. **Input impedance:**
    Very high (ideally infinite) because the input is connected to the op-amp’s non-inverting terminal. This draws almost no current from the source.



