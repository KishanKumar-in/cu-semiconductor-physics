# Experiment-2.3

CO.2 Explain the characteristics and operating principles of various electronic devices including diodes and transistors.

Manual of experiment:

Aim: To analyze the performance of Transistor as Switch.

Apparatus Required:

S.No.

Component/Equipment

Specification

Quantity

1

Transistor

NPN (e.g., BC547) or PNP

1

2

Resistors

1kΩ, 330Ω, 10kΩ

As required

3

LED

Red/Green

1

4

DC Power Supply

0 – 12V

1

5

Switch (push button or toggle)

1

6

Breadboard

1

7

Connecting Wires

As required

8

Multimeter

Digital/Analog

1

Theory:

A Transistor switch, which is used for opening or closing of a circuit that means the transistor, is commonly used as a switch in the electronic devices only for the low voltage applications because of its low power consumption. Transistor work as a switch when it is in cutoff and saturation regions. In this article, we will discuss how to use a transistor as a switch.

Circuit Diagram:

Fig.1 Transistor as a switch

Procedure:

1. Connect the circuit that shown in the figure as shown above.

2. Set the AC source (4V) and frequency (200 HZ) (Square wave) and draw it.

3. Set the oscilloscope (first terminal) at the common terminal of collector and resistance (RL) and (second terminal of OSC) to the emitter of transistor.

Operating Regions:

We can observe from the  characteristics, the pink shaded area at the bottom of the curves represents the Cut-off region and the blue area to the left represent the Saturation region of the transistor. These transistor regions are defined as

Fig.2 Characteristics of Transistor As A Switch

Cut-off Region: The operating conditions of the transistor are zero input base current (IB=0), zero output collector current(Ic=0), and maximum collector voltage (VCE) which results in a large depletion layer and no current flowing through the device. Therefore, the transistor is switched to “Fully-OFF”. So we can define the cut-off region when using a bipolar transistor as a switch as being, bother the junctions of NPN transistors are reverse biased, VB< 0.7v and Ic=0. Similarly, for PNP transistor, the emitter potential must be –ve with respect to the base of the transistor.

Saturation Region: In this region, the transistor will be biased so that the maximum amount of base current (IB) is applied, resulting in maximum collector current(IC=VCC/RL) and then resulting in the minimum collector-emitter voltage (VCE ~ 0) drop. At this condition, the depletion layer becomes as small as the possible and maximum current flowing through the transistor. Therefore, the transistor is switched “Fully-ON”.

Observation Table:

S.No.

Base Voltage (Vb)

Collector Voltage (Vc)

LED State

Transistor Region

1

0V

High (~Vcc)

OFF

Cutoff

2

>0.7V

Low (~0.2V)

ON

Saturation

Calculations (if applicable):

Base current (Ib) = (Vinput – Vbe) / Rb

Collector current (Ic) ≈ (Vcc – Vce) / Rc

Check if Ic ≈ β × Ib (only in active region)

But for switching mode:

Focus on ensuring Vce(sat) ≈ 0.2V in ON state

And Ic ≈ 0 in OFF state

Result:

The experiment successfully demonstrates the working of a transistor as a switch. The transistor remains OFF in the absence of base current and turns ON when a sufficient base current is provided.

Relevant Demonstrative Video LINK:

- Relevant Book/Standard Code: https://qti.stu.edu.iq/wp-content/uploads/2019/12/lab.5-power-electronics.pdf

- Other Resource materials or Web Links: https://ade2-iitr.vlabs.ac.in/exp/bjt-transistor/theory.html