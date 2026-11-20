# Experiment-2.3 - Complete Study Material


## 📘 LECTURE NOTES & EXPLANATIONS


### Experiment-2.3
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

---


## 🖥️ PRESENTATION SLIDES


# Experiment-2.3 - All Lecture Slides Text


## Exp. 2.3
### Slide 1
- UNIVERSITY INSTITUTE OF ENGINEERING
- ENGINEERING FOUNDATION-[EF1-EF5]
- PROGRAME NAME: BE CSE
- ALL BRANCHES/1st
- SEMICONDUCTOR PHYSICS AND APPLICATIONS
- (26SPH-143)
- Unit No.  2                    Exp. 2.3	Lecture No.6
- Topic :To analyze the performance of Transistor as Switch.
- Faculty Name and
- E_Code
- : Dr. Akhil[E7113]    Designation: Associate Professor
- Academic Session 2026-27
- ODD Semester Jul-Dec 2026

### Slide 2
- Learning Objectives
- Students will be able to understand the basic behavior of transistor a switch.
- Students will be able to identify characteristics curve of
- transistor a switch.
- Students will be able to determine specific parameters transistor a switch.
- 1

### Slide 3
- Transistor As A Switch
- A transistor can be used for switching operation for opening or closing of a circuit.
- The transistor as a switch is used for turning ON or OFF a circuit and the transistor is used as an amplifier for amplifying the current.
- Figure-1 : Transistor As Switch [https://circuitglobe.com/common-base-connection-cb-configuration.html]
- 2

### Slide 4
- Cut-Off Region of Transistor [NPN]
- In the cut-off region of the transistor, it operates under conditions of zero input base current (
- Ib
- ), zero output collector current (
- Ic
- ), and maximum collector voltage (
- Vce
- ).
- Figure-2 : Cut off Region [https://www.geeksforgeeks.org/transistor-as-a-switch/]
- 3

### Slide 5
- Cut-Off Region of Transistor [NPN]
- The input and base are grounded.
- Base emitter voltage
- Vbe
- <0.7v
- Base Emitter junctions is reversed.
- Base- collector junction us reversed biased.
- Transistor is "fully-Off" (cut off region)
- No collector current flows(
- Ic
- =0)
- Vout
- =
- Vcr
- =
- Vcc
- = 1
- Transistor operates as open switch.
- 4

### Slide 6
- Saturation Region of Transistor [NPN]
- In this mode of operation, both the emitter-base and collector-base junctions are forward biased.
- In this mode, the transistor is fully switched ON and is essentially a close circuit.
- Figure-3 : Saturation Region [https://www.geeksforgeeks.org/transistor-as-a-switch/]
- 5

### Slide 7
- Saturation Region of Transistor [NPN]
- The base and input are connected to
- Vcc
- .
- Base-Emitter voltage
- Vbe
- >0.7V.
- Base-Emitter junction is forward biased.
- Base-collector junction is forward biased.
- Transistor is "fully-On"
- Max Collector current flows (
- Ic
- =
- Vcc
- /
- Rl
- )
- Vce
- =0 (ideal saturation)
- Transistor operates as a closed switch.
- 6

### Slide 8
- Circuit Diagram of Transistor
- 7

### Slide 9
- Characteristics of Transistor
- 8

### Slide 10
- Applications of Transistor
- Used as electronic ON/OFF switches.
- Audio
- amplifiers
- .
- Radio
- frequency
- (RF)
- amplifiers
- .
- Clock
- signal
- generators
- .
- Linear
- voltage
- regulators
- (e.g.,
- series
- pass
- transistor).
- 9

### Slide 11
- Summary of the Lecture
- 1. We have designed configuration of transistor as switch.
- 2. We have observed performance of transistor as switch.
- 3. We have drawn V-I curve of
- transistor as switch.
- 10

### Slide 12
- Next
- Experiment
- To Verify Kirchhoff’s voltage Law.
- 11

### Slide 13
- Quiz/ FAQ’s
- Q.1: What is a transistor?
- Q.2: Explain working
- of
- transistor
- as switch.
- Q.3: Discuss specific parameters of
- transistor
- as switch.
- 1
- 2

### Slide 14
- R
- eferences/ Articles/ Videos
- https://www.geeksforgeeks.org/transistor-as-a-switch/
- https://www.electronicshub.org/transistor-as-a-switch/
- 1
- 3

### Slide 15
- Faculty-curated videos, NPTEL, Coursera, LinkedIn, or other relevant learning resources
- https://www.coursera.org/learn/transistor-field-effect-transistor-bipolar-junction-transistor
- https://www.tinkercad.com/things/f5gz7Oyt3Qb-
- 14

### Slide 16
- Class-Wise
- Feedback
- Faculty members are encouraged to generate a class specific QR code at the end of each session to collect brief student feedback. This can support self-reflection, improve teaching practices, and allow students to share insights, suggestions, or concerns anonymously.
- 15

### Slide 17
- Thank You
- For queries
- Email: akhilnigam.eee@cumail.in
- 16


---
