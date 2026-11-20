# Experiment-1.3

CO.2: Explain the characteristics and operating principles of various electronic devices including diodes and transistors.

Manual of the experiment:

Aim: To implement half wave rectifier with and without filter and to determine ripple factor.

## Apparatus Required:

S. No.

Apparatus

Specification

Quantity

1.

Diode

IN4007 or equivalent

1

2.

Transformer

230V/12V, step-down

1

3.

Resistor (Load)

1 kΩ

1

4.

Capacitor (for filter)

1000 μF, 25V

1

5.

CRO or Oscilloscope

Dual Channel

1

6.

Multimeter

–

1

7.

Breadboard / Circuit board

–

1

8.

Connecting wires

–

As needed

## Equipment:

S.No.

Name

Quantity

1

Transformer with Center Tapped Secondary ( 9 - 0 - 9 ) V

1 (One) No.

2

Digital Multimeter/ Digital Voltmeter (0-20V)

1 (One) No.

3

Cathode Ray Oscilloscope (CRO) (0-20MHz)

1 (One) No.

4

Connecting wires (Single Strand)

##

## Theory:

The conversion of AC into DC is called Rectification. Electronic devices can convert AC power into DC power with high efficiency. The efficiency of the Half Wave Rectifier is 40.6%.

Consider the given circuit. Assume the diode to be ideal i.e. Vf = 0,  Rr =infinite, Rs = 0.

During the positive half cycle, the diode is forward biased and it conducts and hence a current flows through the load resistor. During the negative half cycle, the diode is reverse biased and it is equivalent to an open circuit, hence the current through the load resistance is zero.

Thus the diode conducts only for one half cycle and results in a half wave rectified output.

During positive half-cycle of the input voltage, the diode D1 is in forward bias and conducts    through the load resistor RL. Hence the current produces an output voltage across the load resistor RL, which has the same shape as the +ve half cycle of the input voltage.

During the negative half-cycle of the input voltage, the diode is reverse biased and there is no current through the circuit. i.e., the voltage across RL is zero. The net result is that only the +ve half cycle of the input voltage appears across the load. The average value of the half wave rectified o/p voltage is the value measured on dc voltmeter.

For practical circuits, transformer coupling is usually provided for two reasons.

1. The voltage can be stepped-up or stepped-down, as needed.

2. The ac source is electrically isolated from the rectifier. Thus preventing shock hazards in the secondary circuit.

A Half Wave Rectifier allows only one half-cycle (positive or negative) of the AC input to pass, blocking the other. The output is a pulsating DC.

A filter (typically a capacitor) is used to reduce ripples and smooth the output.

Ripple Factor (γ) is defined as:

Ripple Factor (γ)=Vrms (AC)VDC\text{Ripple Factor (γ)} = \frac{V_{\text{rms (AC)}}}{V_{\text{DC}}}

For ideal DC, ripple factor = 0.

## Circuit Diagrams:

1. Half Wave Rectifier (Without Filter):

Fig.1 Half wave rectifier without filter

Fig.2 Half wave rectifier with filter

## Procedure:

A. Without Filter:

Connect the circuit as per the HWR diagram without a capacitor.

Connect the primary of the transformer to AC mains ac mains and the secondary side to the rectifier input.

By the multimeter, measure the ac input voltage of the rectifier and, ac and dc voltage at the output of the rectifier.

Observe the output waveform across the load resistor using a CRO.

Measure the DC voltage and AC voltage (ripple) across the load using a multimeter or CRO.

Find the theoretical value of dc voltage by using the formula, Vdc=Vm/П

Where, Vm=2Vrms, (Vrms=output ac voltage.)

The Ripple factor is calculated by using the formula

r = ac output voltage/dc output voltage.

## B. With Filter:

Add a capacitor in parallel with the load resistor.

Again, observe the output waveform.

Measure the DC output voltage and the ripple voltage.

Note how the capacitor smoothens the waveform.

##

## Observation Table:

S. No.

Condition

V<sub>DC</sub> (V)

V<sub>rms (AC)</sub> (V)

Ripple Factor (γ)

1

Without Filter

…

…

…

2

With Filter

…

…

…

Calculation for Ripple Factor:

Without filter:

Vrms= Vmax/2

Vm= 2Vrms

Vdc= Vmax/π

Ripple Factor=  = 1.21

MODEL WAVEFORMS:

Outcomes: Students are able to

- analyze the operation of Half Wave rectifier with and without filter.

- calculate its performance parameters-ripple factor, percentage regulation, efficiency with and without filter.

## Result:

The Half Wave Rectifier successfully converts AC to pulsating DC.

The addition of a capacitor significantly reduces ripple.

Ripple factor is high without a filter and much lower with a filter.

## Precautions:

Use the capacitor with correct polarity and voltage rating.

Do not touch circuit components when powered.

Ensure proper connections before switching on the supply.

Discharge capacitor safely before handling.

Relevant Demonstrative Video LINK:

- Relevant Book/Standard Code: https://vikramlearning.com/jntuh/notes/electronic-devices-and-circuits-lab/half-wave-rectifier-with-and-without-filters/4

- Other Resource materials or Web Links: https://vikramlearning.com/jntuh/notes/electronic-devices-and-circuits-lab/half-wave-rectifier-with-and-without-filters/4