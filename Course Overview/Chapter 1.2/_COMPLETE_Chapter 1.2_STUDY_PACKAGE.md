# Chapter 1.2 - Complete Study Material


## 📘 LECTURE NOTES & EXPLANATIONS


### Lecture Topic 1.2.1
# Lecture Topic 1.2.1

CO.2: Explain the characteristics and operating principles of various electronic devices including diodes and transistors.

Introduction, Half Wave Rectifier and its Analysis:

## Rectifier:

A rectifier is an electronic component that converts alternating current (AC) into direct current (DC), ensuring a unidirectional flow of electric charge. As we know, electricity reaches our homes from power grids in the form of AC, but most commonly used electric appliances, such as mobile phones, computers, televisions, fridges, etc, operate on direct current (DC). Therefore, the rectifier becomes a very useful component in electronics.

Rectifiers are electronic devices or circuits that convert alternating current (AC) into direct current (DC). Alternating current periodically changes direction, whereas direct current flows consistently in one direction. Rectifiers are crucial in many electronic applications where a steady DC voltage is required.

Most rectifiers use P-N junction diodes to convert AC to DC, but some use different kinds of materials as well, such as semiconductor materials like silicon carbide or specialized semiconductor devices like thyristors and metal-oxide-semiconductor field-effect transistors (MOSFETs).

## How does Rectifier Work?

A rectifier is an electrical device which is used to convert AC current into DC current. Rectifier does this process by allowing current (I) to flow through any device and the process taking place here is called rectification.

Rectifier works by using diodes which are like one-way valves for electricity. A rectifier can take one or more diodes to convert the positive or negative half cycle of the AC inputs DC outputs. Rectifiers generates an DC voltage by rectifying any one cycle of the AC supply and the reverse operation of this above process is called Inverter and the process called inversion in electricity.

## Rectifiers Circuits

It plays a vital role in DC power supplies for converting AC signal into DC signal. P-N junction diode have lot of applications and Rectifier circuits are one of them. In simple words the electronic circuit which performs rectification is called rectifier circuit. By using this circuit we can able to convert electrical signals.

## Types of Rectifiers

There are various types of rectifiers used in electronics for different use cases. Some of these rectifiers are:

Half-Wave Rectifier

- The simplest type of rectifier.

- Uses a single diode to allow current to flow in only one direction during one half-cycle of the AC waveform.

- Efficiency is relatively low.

Full-Wave Rectifier

- Utilizes two diodes to rectify both halves of the AC waveform.

- Improved efficiency compared to half-wave rectifiers.

Center-Tap Full-Wave Rectifier: Uses a center-tapped transformer.

Bridge Rectifier: Uses four diodes in a bridge configuration, eliminating the need for a center-tapped transformer.

Bridge Rectifier

- A type of full-wave rectifier that uses four diodes in a bridge configuration.

- More efficient than center-tap full-wave rectifiers.

- Commonly used in power supplies and electronic devices.

## Half Wave Rectifier:

A Half-wave rectifier is an electronic device that is used to convert Alternating current (AC) to Direct current (DC). A half-wave rectifier allows either a positive or negative half-cycle of AC to pass and blocks the other half-cycle. Half-wave rectifier selectively allows only one half-cycle of the AC input voltage to pass through, producing a pulsating DC output voltage across the load resistor. While it's a simple and cost-effective way to convert AC to DC.

## Half Wave Rectifier Circuit

Given below is the Circuit diagram of the Half Wave Rectifier. The components of the Half Wave Rectifier are P-N Junction diode, Ac supply and the load.

Fig.1 Half Wave Rectifier

## Construction of Half Wave Rectifier

To Construct a half-wave rectifier, the Components are Assembled as the Following

- Function generator serves as input AC source for us. The positive end of the function generator (red colored end) is connected to the positive side of the diode(black side of diode without line).

- Next, The negative terminal of the diode (marked by a grey line or indicator) is connected to the one end of the resistor.

- Now, The other end of the resistor is connected to the remaining terminal of the function generator. This completes the circuit loop and allows the AC signal from the function generator to flow through the diode and resistor.

## Working of Half Wave Rectifier

In a half-wave rectifier, the AC supply is connected in series to a p-n junction diode and load resistor. An Alternating current (AC) consists of two half-cycles: Positive half-cycle and Negative half-cycle. Let us take a look at the working of the half-wave circuit at each half-cycle separately.

- In a positive half-cycle, the Diode is forward-biased and hence acts like a short circuit. Therefore in a positive half-cycle, current flows through the circuit and produces whole AC input as such in DC output. In the real world, the output voltage is less than the input voltage considering the Diode voltage drop.

- In a negative half-cycle, the Diode is reverse-biased and hence acts like an open circuit. Therefore, in a negative half-cycle current does not flow through the circuit. And output does not consist of input negative half-cycle.

The below figure shows the output waveform of the DC output waveform of a half-wave rectifier. From the input first a positive half cycle comes and in the positive half cycle diode lets pass the input voltage through it. You can see the positive half cycle in the output waveform as such from the input waveform. Then a negative half-cycle comes, but it does not allow to pass the negative half-cycle and we can see that the negative half-cycle is not present in the output waveform. At that time output voltage is zero. Then again a positive half cycle comes which is passed through the diode and it is visible in the output waveform. After that a negative half cycle comes and it is blocked by the diode and is not present in the output. This process continues to convert AC to DC.

fig.2 Output waveform of half wave rectifier

Relevant Video links for this lecture topic:

- Relevant Books readings (Web Links / Web Links of PDFs) for this lecture topic: https://www.geeksforgeeks.org/half-wave-rectifier/

- Any web-link to be attached relevant to the topic: https://www.electrical4u.com/half-wave-rectifiers/

---


### Lecture Topic 1.2.2
# Lecture Topic 1.2.2

CO.2 Explain the characteristics and operating principles of various electronic devices including diodes and transistors.

Full Wave Rectifier and its Analysis:

A full wave rectifier is defined as a rectifier that converts the complete cycle of alternating current into pulsating DC.

## Full Wave Rectifier Circuit

The circuit of the full wave rectifier can be constructed in two ways. The first method uses a centre tapped transformer and two diodes. This arrangement is known as a centre tapped full wave rectifier. The second method uses a standard transformer with four diodes arranged as a bridge. This is known as a bridge rectifier. In the next section, we will restrict the discussion to the centre tapped full wave rectifier only. You can read our article on bridge rectifier to learn the construction and working of bridge rectifier in detail.

## Working of Full Wave Rectifier

- Rectification: Converts AC to pulsating DC by allowing current flow in both halves of the AC cycle using diodes.

- Bridge Configuration: Often employs a bridge rectifier with four diodes to ensure full-wave rectification.

- Output Voltage: Produces a pulsating DC output with twice the frequency of the input AC.

## Types of Full Wave Rectifiers

A full wave rectifier is an electronic circuit that converts alternating current (AC) into direct current (DC), and it has two main types:

- Center-Tapped Full Wave Rectifier: It uses a center-tapped transformer and two diodes to rectify AC, commonly employed in low to moderate power applications.

- Bridge Rectifier: This type of bridge rectifier utilizes four diodes arranged in a bridge configuration allowing for AC to DC conversion without relying on a center tapped transformer. It is often employed in high power applications and compact circuits.

## Bridge Rectifier Full Wave Rectifier:

A wave rectifier that doesn't need a center-tapped transformer is a bridge rectifier circuit. Instead, it converts both of the input cycle's negative components using four diodes arranged in a bridge arrangement.

In this circuit, the diodes are positioned so that two conduct during one half of the input cycle and the other two conduct during the other. By ensuring that both input cycle halves are rectified, a current (DC) output waveform is produced.

fig.1 Full wave bridge rectifier

fig.2 Output of full wave rectifier

## Advantages of Bridge Rectifier Full Wave Rectifier

- The efficiency of rectifying a bridge is higher when compared to a half wave rectifier.

- The ripple factor is lower which leads to a DC output waveform.

- Bridge rectifiers are a cost option as they eliminate the need, for a center tapped transformer, unlike center tapped rectifiers.

## Disadvantages of Bridge Rectifier Full Wave Rectifier

- While using bridge rectifiers there is a decrease, in voltage due to the process of rectification.

- Setting up bridge rectifiers involves a circuit arrangement, which might pose challenges for those who are new to electronics.

- The components used in bridge rectifiers such as diodes can be more expensive compared to rectification methods.

- Multiple diodes in bridge rectifiers can generate heat so it's important to include heat dissipation solutions like heat sinks.

- Bridge rectifiers may exhibit leakage currents, where a small amount of current flows, in the opposite direction when the diodes are off. This can result in energy wastage and reduced efficiency.

Relevant Video links for this lecture topic:

- Relevant Books readings (Web Links / Web Links of PDFs) for this lecture topic: https://www.geeksforgeeks.org/full-wave-rectifier/

- Any web-link to be attached relevant to the topic: https://byjus.com/physics/full-wave-rectifier/

---


### Lecture Topic 1.2.3
# Lecture Topic 1.2.3

CO.4: Illustrate the characteristics of diodes, different types of transistors, and the basic concepts of electric circuits.

Center Tap Rectifier and its Analysis:

Fig.1 Center tapped full wave rectifier

A center-tapped full wave rectifier circuit consists of a center-tapped transformer, two diodes, and a resistive load. The center-tapped transformer has a wire connected at the center of its secondary winding, which divides the input AC voltage into two halves. The diodes are connected in parallel to each other, with the load connected at the center tap of the transformer.

During the positive half of the input cycle, one diode conducts (forward bias) while the other diode is non-conducting (reverse bias). This allows current to flow through the load. In the negative part of the cycle, the diodes change their job. The one that was allowing electricity to flow now stops, and the one that was blocking it begins to allow it through. This is unlike a half-wave rectifier that uses only one part of the cycle. Using both parts in a full wave rectifier improves its performance and ensures more efficient conversion of the wavy input into a smooth output.

## Working of Centre-Tapped Full Wave Rectifier:

Fig.2 Input-Output Curve of center tapped rectifier

## Advantages of Centre-Tapped Full Wave Rectifier

- Some advantages of using a center tapped wave include its higher efficiency compared to a half wave rectifier since it utilizes both halves of the AC cycle.

- It produces an more consistent DC output waveform, which reduces noise in devices.

- This type of rectifier plays a role in converting AC to DC and providing reliable power, for various electronic applications.

- The voltage and current, in the DC are twice as high as those in a half wave rectifier resulting in increased power, for the devices connected to it.

## Disadvantages of Centre-Tapped Full Wave Rectifier

- The rectifier necessitates the use of center tapped transformers, which can be more costly to produce and thus raise the circuit expenses.

- Designing and constructing it is more intricate when compared to a half wave rectifier, which makes it less appropriate, for simple applications.

- The transformer utilized in this rectifier can be bigger and heavier which may not be optimal, for portable devices.

Relevant Video links for this lecture topic:

- Relevant Books readings (Web Links / Web Links of PDFs) for this lecture topic: https://www.geeksforgeeks.org/full-wave-rectifier/

- Any web-link to be attached relevant to the topic: https://byjus.com/physics/full-wave-rectifier/

---


### Lecture Topic 1.2.4
# Lecture Topic 1.2.4

CO.4 Illustrate the characteristics of diodes, different types of transistors, and the basic concepts of electric circuits.

Merits and Demerits of Rectifiers, Comparison between Rectifiers:

## Advantages of Rectifiers

Main advantages of rectifiers are:

- Converts AC to DC power for electronic devices.

- Essential for battery charging in devices and electric vehicles.

- Used in industrial processes like electroplating and welding.

- Enables efficient HVDC power transmission over long distances.

- Provides controlled and stable DC power for precision applications.

- Integral in renewable energy systems for converting variable AC to DC.

- Facilitates signal processing by converting AC signals to rectified signals.

- Contributes to energy efficiency in power conversion processes.

- Cost-effective and reliable for a wide range of applications.

## Disadvantages of Rectifiers

Key disadvantages of rectifiers are:

- Generates harmonics and electrical noise during the conversion process.

- May require additional filtering components to reduce output ripple.

- Limited in handling high power levels compared to some alternative technologies.

- Efficiency can decrease at partial loads or when operating away from design conditions.

- High initial costs for certain types of rectifiers and associated equipment.

- Some rectifiers may have a relatively lower power factor, leading to poor power quality.

- Maintenance may be required, especially in heavy industrial applications.

- Possibility of heat generation, requiring cooling mechanisms in high-power rectifiers.

- Incompatible with AC-powered devices, necessitating additional conversion for certain applications.

- Environmental concerns, as certain types of rectifiers may contain hazardous materials.

## Applications of Rectifiers

Some of the key application of rectifiers are:

- It is used for powering appliances as we know all electrical appliances use a DC power supply to function. By using rectifier in power supply and systems it helps in conversion of AC to DC.

- It is used to soldering and modulation as it is used in mosquito repellent to power the lead for the fumes.

- Voltage multiplier - As said earlier that rectifiers are used for power conversion such as AC power to DC power and so on same as they are used to convert AC to DC voltage for electronic appliances such as microwave ovens and so on.

- Used in Transformers to obtain desired voltage by using rectifier in combination with a step-down or step-up transformer.

- For Radio appliances rectifiers acts as an detectors because the output consists of an audio signals. For examples Modulation, Demodulation and power supplies.

## Difference Between Full Wave and Bridge Rectifier

Aspect

Full Wave Rectifier

Bridge Rectifier

Definition

The full wave rectifier comprises of two diodes which makes it capable for handling higher voltage.

The bridge rectifier consists of four diodes connected together to display the condition of Wheatstone bridge.

Peak Inverse Voltage

Max 2 Vs

Vs Max

Voltage Regulation

Better

Good

Transformer Utilization Factor

0.692

0.812

Load Current at Peak

VsMaxRL+RF

RL​+RF​VsMax​

VsMaxRL+2RF

RL​+2RF​VsMax​

Requirement of Transformer

Compulsory

Option or Not Required

Voltage Drop across Diode

Low

High

Number of Diodes

2

4

Circuit Complexity

Low

High

Relevant Video links for this lecture topic:

- Relevant Books readings (Web Links / Web Links of PDFs) for this lecture topic: https://www.geeksforgeeks.org/bridge-rectifier/

- Any web-link to be attached relevant to the topic: https://www.geeksforgeeks.org/rectifier/

---


### Lecture Topic 1.2.5
# Lecture Topic 1.2.5

CO.4 Illustrate the characteristics of diodes, different types of transistors, and the basic concepts of electric circuits.

Numerical Based On rectifiers:

## Q. Consider half wave rectifier is working on 200V (RMS Value) input voltage, 50 Hz AC power supply. Then analyze its DC output voltage, RMS output voltage and peak inverse voltage.

## Solution.

---


## 🖥️ PRESENTATION SLIDES


# Chapter 1.2 - All Lecture Slides Text


## 1.2.1
### Slide 1
- UNIVERSITY INSTITUTE OF ENGINEERING
- ENGINEERING FOUNDATION-[EF1-EF5]
- PROGRAME NAME: BE CSE
- ALL BRANCHES/1st
- SEMICONDUCTOR PHYSICS AND APPLICATIONS
- (26SPH-143)
- Unit No.  1                    Chapter No.2	Lecture No.6
- Topic :Introduction, Half Wave Rectifier and its Analysis
- Faculty Name and
- E_Code
- : Dr. Akhil[E7113]    Designation: Associate Professor
- Academic Session 2026-27
- ODD Semester Jul-Dec 2026

### Slide 2
- Learning Objectives
- Students will be able to understand about rectifier.
- Students will be able to understand basic construction of half wave rectifier with its analysis.
- Students will be able
- to remember applications of rectifier.
- 1

### Slide 3
- Recap of Previous Lecture
- If the lecture is in continuity, then list down the topics covered in the previous lecture.
- Working principles of Zener Diode, Volt-Ampere Characteristics, Zener diode Applications
- 2

### Slide 4
- Rectifier
- A rectifier is an electronic circuit that converts alternating current (AC) to direct current (DC). This process is called rectification.
- Types are Half-Wave Rectifier & Full Wave Rectifier.
- Figure-1 : Rectifier [https://www.etechnog.com/2022/04/what-is-rectifier-block-diagram-working.html]
- 3

### Slide 5
- Rectifier Components
- P-N junction diode:
- A p-n junction diode is a device that only allows current flow in one direction.
- Alternating Current (AC): It is an electric current that changes its direction periodically.
- DC Current (DC): It is a type of electric current that does not change its direction periodically.
- Capacitor: A capacitor is a two-terminal device that stores energy in the form of electric field.
- 4

### Slide 6
- Types of Rectifier
- Half Wave rectifier:
- A half-wave rectifier allows one AC half-cycle to pass through it and blocks the other AC half-cycle. Therefore, it is called a half-wave rectifier.
- Full wave rectifier:
- A Full wave rectifier can convert both AC half cycle to DC. It allows a one-half cycle of AC without any modification. And other half cycle is also allowed to pass but it reverses the direction of that half cycle.
- 5

### Slide 7
- Half Wave Rectifier
- Half-wave rectifiers transform AC voltage to DC voltage. A halfwave rectifier circuit uses only one diode for the transformation.
- A half-wave rectifier is the simplest form of the rectifier and requires only one diode for the construction
- Figure-2 : Half Wave Rectifier[https://www.sciencefacts.net/half-wave-rectifier.html]
- 6

### Slide 8
- Working of Half Wave Rectifier
- A high AC voltage is applied to the primary side of the step-down transformer. The obtained secondary low voltage is applied to the diode.
- The diode is forward biased during the positive half cycle of the AC voltage and reverse biased during the negative half cycle.
- 7

### Slide 9
- Half Wave Rectifier With Filter
- We can make the output of half wave rectifier smooth by using a filter (a capacitor filter or an inductor filter) across the diode.
- Additional / Recommended Readings:
- https://www.circuitdiagram.co/circuit-diagram-of-zener-diode-experiment/
- Figure.3 Half Wave Rectifier With filter
- 8

### Slide 10
- Applications of Rectifier
- In
- p
- owering
- appliances
- .
- Voltage multiplier.
- Used
- in Transformers
- For Radio
- appliances
- rectifiers
- .
- 9

### Slide 11
- Summary of the Lecture
- 1. We have studied about rectifiers.
- 2. We have differentiated between
- half wave and full wave rectifier.
- 3. We have studied about applications of rectifier.
- 10

### Slide 12
- Next
- Topic
- Full Wave Rectifier and its Analysis
- 11

### Slide 13
- Quiz/ FAQ’s
- Q.1: How rectifier converts AC into DC?
- Q.2:
- Explain construction of half wave rectifier.
- Q.3: What are applications of rectifiers?
- 1
- 2

### Slide 14
- R
- eferences/ Articles/ Videos
- https://www.geeksforgeeks.org/half-wave-rectifier/
- https://byjus.com/physics/half-wave-rectifier/
- https://www.mangoengineer.in/2024/05/half-waver-rectifier.html
- 1
- 3

### Slide 15
- Faculty-curated videos, NPTEL, Coursera, LinkedIn, or other relevant learning resources
- https://www.coursera.org/learn/modeling-and-control-of-single-phase-rectifiers-and-inverters
- https://nptel.ac.in/courses/117108124
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


## 1.2.2
### Slide 1
- UNIVERSITY INSTITUTE OF ENGINEERING
- ENGINEERING FOUNDATION-[EF1-EF5]
- PROGRAME NAME: BE CSE
- ALL BRANCHES/1st
- SEMICONDUCTOR PHYSICS AND APPLICATIONS
- (26SPH-143)
- Unit No.  1                    Chapter No.2	Lecture No.7
- Topic :Full Wave Rectifier and its Analysis
- Faculty Name and
- E_Code
- : Dr. Akhil[E7113]    Designation: Associate Professor
- Academic Session 2026-27
- ODD Semester Jul-Dec 2026

### Slide 2
- Learning Objectives
- Students will be able to understand about full wave rectifier.
- Students will be able to understand basic construction of full wave wave rectifier with its analysis.
- Students will be able
- to analyze working of full wave rectifier.
- 1

### Slide 3
- Recap of Previous Lecture
- If the lecture is in continuity, then list down the topics covered in the previous lecture.
- Fundamentals of rectifier, half wave rectifier with its construction and working principles, applications of rectifier.
- 2

### Slide 4
- Full Wave Rectifier
- A full wave rectifier is a component, in electronics that converts alternating current (AC) into direct current (DC).
- A wave rectifier circuit is used to convert an input AC signal into DC by rectifying both negative cycles.
- Figure-1 : Full wave rectifier [https://www.mangoengineer.in/2024/08/Full-Wave-Rectifier-Formulas.html]
- 3

### Slide 5
- Specifications of Full Wave Rectifier
- Like the half wave circuit, a full wave rectifier circuit produces an output voltage or current which is purely DC or has some specified DC component. Full wave rectifiers have some fundamental advantages over their half wave rectifier counterparts.
- The average (DC) output voltage is higher than for half wave, the output of the full wave rectifier has much less ripple than that of the half wave rectifier producing a smoother output waveform.
- 4

### Slide 6
- Working of Full Wave Rectifier
- Rectification:
- Converts AC to pulsating DC by allowing current flow in both halves of the AC cycle using diodes.
- Bridge Configuration:
- Often employs a bridge rectifier with four diodes to ensure full-wave rectification.
- Output Voltage:
- Produces a pulsating DC output with twice the frequency of the input AC.
- 5

### Slide 7
- Bridge Type Full Wave Rectifier
- In this circuit, the diodes are positioned so that two conduct during one half of the input cycle and the other two conduct during the other. By ensuring that both input cycle halves are rectified, a current (DC) output waveform is produced.
- Figure-2 : Bridge Type Full wave rectifier [https://www.geeksforgeeks.org/full-wave-rectifier/]
- 6

### Slide 8
- Working of Bridge Type Full Wave Rectifier
- When the AC power goes through this bridge, during each half of the cycle, two of these diodes start working like a team.
- This setup ensures that both the positive and negative parts of the AC electricity get turned into DC
- Figure-3 : Bridge Type Full wave rectifier [https://www.geeksforgeeks.org/full-wave-rectifier/]
- 7

### Slide 9
- Advantages of Full Wave Rectifier
- The efficiency of rectifying a bridge is higher when compared to a half wave rectifier.
- The ripple factor is lower which leads to a DC output waveform.
- Bridge rectifiers are a cost option as they eliminate the need, for a center tapped transformer, unlike center tapped rectifiers.
- 8

### Slide 10
- Disa
- dvantages of Full Wave Rectifier
- While using bridge rectifiers there is a decrease, in voltage due to the process of rectification.
- Setting up bridge rectifiers involves a circuit arrangement, which might pose challenges for those who are new to electronics.
- The components used in bridge rectifiers such as diodes can be more expensive compared to rectification methods.
- 9

### Slide 11
- Formulae
- of Full Wave Rectifier
- Bridge Rectifier Formula:
- Vout
- =
- Vm
- –
- Vd
- Where:
- Vout
- is the output DC voltage.
- Vm
- is the peak value of the AC voltage (maximum voltage).
- Vd
- is the voltage drop across the diodes (usually around 0.7 volts for silicon diodes).
- 10

### Slide 12
- Peak Inverse Voltage
- of Full Wave Rectifier
- PIV is the maximum reverse voltage that a diode in a full-wave rectifier must withstand. It is equal to the peak value of the input AC voltage.
- PIV=
- Vm
- where,
- Vm
- = peak value of the AC input voltage
- 11

### Slide 13
- Rectification Efficiency
- of Full Wave Rectifier
- Rectification efficiency measures how effectively the rectifier converts AC to DC. It is the ratio of the DC power output to the AC power input. The efficiency of the full wave rectifiers is 81.2%.
- η
- =
- [
- Pdc
- / Pac
- ​] ​​∗100
- 12

### Slide 14
- Applications of Full Wave Rectifier
- Power
- Supply
- Units
- Radio and
- Television
- Sets
- Battery
- Charging
- Circuits
- Welding
- Equipment
- Measurement
- Devices
- 13

### Slide 15
- Summary of the Lecture
- 1. We have studied about full wave rectifier.
- 2. We have illustrated about construction of full wave rectifier.
- 3. We have studied about applications of full wave rectifier.
- 14

### Slide 16
- Next
- Topic
- Center Tap Rectifier and its Analysis
- 15

### Slide 17
- Quiz/ FAQ’s
- Q.1: How full wave rectifier converts AC into DC?
- Q.2:
- Explain construction of full wave rectifier.
- Q.3: What are applications of full wave rectifier?
- 1
- 6

### Slide 18
- R
- eferences/ Articles/ Videos
- https://www.electricalvolt.com/full-wave-rectifier-working-types-circuit-diagrams/
- https://www.electronics-tutorials.ws/diode/diode_6.html
- https://www.geeksforgeeks.org/full-wave-rectifier/
- 1
- 7

### Slide 19
- Faculty-curated videos, NPTEL, Coursera, LinkedIn, or other relevant learning resources
- https://www.coursera.org/learn/modeling-and-control-of-single-phase-rectifiers-and-inverters
- https://nptel.ac.in/courses/117108124
- 18

### Slide 20
- Class-Wise
- Feedback
- Faculty members are encouraged to generate a class specific QR code at the end of each session to collect brief student feedback. This can support self-reflection, improve teaching practices, and allow students to share insights, suggestions, or concerns anonymously.
- 19

### Slide 21
- Thank You
- For queries
- Email: akhilnigam.eee@cumail.in
- 2
- 0


## 1.2.3
### Slide 1
- UNIVERSITY INSTITUTE OF ENGINEERING
- ENGINEERING FOUNDATION-[EF1-EF5]
- PROGRAME NAME: BE CSE
- ALL BRANCHES/1st
- SEMICONDUCTOR PHYSICS AND APPLICATIONS
- (26SPH-143)
- Unit No.  1                    Chapter No.2	Lecture No.8
- Topic :Center Tap Rectifier and its Analysis
- Faculty Name and
- E_Code
- : Dr. Akhil[E7113]    Designation: Associate Professor
- Academic Session 2026-27
- ODD Semester Jul-Dec 2026

### Slide 2
- Learning Objectives
- Students will be able to understand about
- centre
- tapped full wave rectifier.
- Students will be able to understand basic construction of
- centre
- tapped
- full wave wave rectifier with its analysis.
- Students will be able
- to analyze applications of
- centre
- tapped full wave rectifier.
- 1

### Slide 3
- Recap of Previous Lecture
- If the lecture is in continuity, then list down the topics covered in the previous lecture.
- Fundamentals of rectifier, full wave rectifier with its construction and working principles, applications of rectifier.
- 2

### Slide 4
- Centre Tapped Full Wave Rectifier
- A center-tapped full wave rectifier circuit consists of a center-tapped transformer, two diodes, and a resistive load.
- The diodes are connected in parallel to each other, with the load connected at the center tap of the transformer.
- Figure-1 : Centre Tapped Full wave rectifier [https://www.geeksforgeeks.org/full-wave-rectifier/]
- 3

### Slide 5
- Specifications of Centre
- Tapped
- Full Wave Rectifier
- The center-tapped transformer has a wire connected at the center of its secondary winding, which divides the input AC voltage into two halves.
- During the positive half of the input cycle, one diode conducts (forward bias) while the other diode is non-conducting (reverse bias). This allows current to flow through the load. In the negative part of the cycle, the diodes change their job.
- 4

### Slide 6
- Working of Centre Tapped Full Wave Rectifier
- In this arrangement the center tapped full wave rectifier effectively converts AC to DC by utilizing two diodes. During the half of the AC cycle one diode allows current to flow through the connected device or load.
- Conversely during the half of the cycle the other diode takes over. Enables current to flow in the opposite direction.
- 5

### Slide 7
- Centre Tapped Full Wave Rectifier
- The waveforms for the applied input voltage, the flow of current throughout the load & the o/p voltage obtained across the load.
- The center tapped full wave rectifier waveforms are shown as:
- Figure-2 : Centre Type Full wave rectifier [https://www.geeksforgeeks.org/full-wave-rectifier/]
- 6

### Slide 8
- Advantages of Centre Tapped Rectifier
- Some advantages of using a center tapped wave include its higher efficiency compared to a half wave rectifier since it utilizes both halves of the AC cycle.
- It produces an more consistent DC output waveform, which reduces noise in devices.
- This type of rectifier plays a role in converting AC to DC and providing reliable power, for various electronic applications.
- 7

### Slide 9
- Disa
- dvantages of Centre Tapped Rectifier
- The rectifier necessitates the use of center tapped transformers, which can be more costly to produce and thus raise the circuit expenses.
- Designing and constructing it is more intricate when compared to a half wave rectifier, which makes it less appropriate, for simple applications.
- 8

### Slide 10
- Applications of Centre Tapped Rectifier
- This rectifier is used to convert high input AC voltage to low DC voltage.
- These types of rectifiers are used as basic components within the power supply units due to their high efficiency.
- These are used to provide power to motors, LEDs, etc.
- 9

### Slide 11
- Summary of the Lecture
- 1. We have studied about
- centre
- -
- tapped full wave rectifier.
- 2. We have illustrated about construction of
- centre
- -
- tapped
- rectifier.
- 3. We have studied about applications of
- centre
- -
- tapped rectifier.
- 10

### Slide 12
- Next
- Topic
- Merits and Demerits of Rectifiers, Comparison between Rectifiers
- 11

### Slide 13
- Quiz/ FAQ’s
- Q.1: How
- centre
- tapped full wave rectifier converts AC into DC?
- Q.2:
- Explain construction of
- centre
- -
- tapped full wave rectifier.
- Q.3: What are applications of
- centre
- -
- tapped full wave rectifier?
- 1
- 2

### Slide 14
- R
- eferences/ Articles/ Videos
- https://www.elprocus.com/center-tapped-full-wave-rectifier/
- https://www.geeksforgeeks.org/full-wave-rectifier/
- https://www.electrical4u.com/full-wave-rectifiers/
- 1
- 3

### Slide 15
- Faculty-curated videos, NPTEL, Coursera, LinkedIn, or other relevant learning resources
- https://www.coursera.org/learn/modeling-and-control-of-single-phase-rectifiers-and-inverters
- https://nptel.ac.in/courses/117108124
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


## 1.2.4
### Slide 1
- UNIVERSITY INSTITUTE OF ENGINEERING
- ENGINEERING FOUNDATION-[EF1-EF5]
- PROGRAME NAME: BE CSE
- ALL BRANCHES/1st
- SEMICONDUCTOR PHYSICS AND APPLICATIONS
- (26SPH-143)
- Unit No.  1                    Chapter No.2	Lecture No.9
- Topic :Merits and Demerits of Rectifiers, Comparison between Rectifiers
- Faculty Name and
- E_Code
- : Dr. Akhil[E7113]    Designation: Associate Professor
- Academic Session 2026-27
- ODD Semester Jul-Dec 2026

### Slide 2
- Learning Objectives
- Students will be able to understand merits and demerits of rectifiers.
- Students will be able to understand comparison between half wave and full wave rectifiers.
- Students will be able
- to analyze applications of
- half wave and full wave rectifier.
- 1

### Slide 3
- Recap of Previous Lecture
- If the lecture is in continuity, then list down the topics covered in the previous lecture.
- Fundamentals of rectifier,
- centre
- type full wave rectifier with its construction and working principles, applications of rectifier.
- 2

### Slide 4
- Merits of Half Wave Rectifier
- Simplicity of circuit:
- The half-wave rectifier circuit is simple and easy to Implement.
- Low cost:
- Components required for a half-wave rectifier are inexpensive, contributing to cost-less designs.
- Easy to manufacture:
- Due to its Low cost and simple Design, half Wave Rectifiers can be easily manufactured in large quantities.
- 3

### Slide 5
- Demerits of Half Wave Rectifier
- High ripple factor:
- It produces Significant ripple in output Waveform, leading to fluctuations in the DC output voltage.
- High power loss:
- Efficiency is reduced due to the utilization of only half of the input waveform, resulting in higher power dissipation.
- Low efficiency:
- Compared to full-wave rectifiers, half-wave rectifiers have lower efficiency because they utilize only one half of the input cycle.
- 4

### Slide 6
- Merits of Centre Tapped Full Wave Rectifier
- Some advantages of using a center tapped wave include its higher efficiency compared to a half wave rectifier since it utilizes both halves of the AC cycle.
- It produces an more consistent DC output waveform, which reduces noise in devices.
- This type of rectifier plays a role in converting AC to DC and providing reliable power, for various electronic applications.
- 5

### Slide 7
- Dem
- erits of Centre Tapped Full Wave Rectifier
- The rectifier necessitates the use of center tapped transformers, which can be more costly to produce and thus raise the circuit expenses.
- Designing and constructing it is more intricate when compared to a half wave rectifier, which makes it less appropriate, for simple applications.
- The transformer utilized in this rectifier can be bigger and heavier which may not be optimal, for portable devices.
- 6

### Slide 8
- Applications of Centre Tapped Rectifier
- This rectifier is used to convert high input AC voltage to low DC voltage.
- These types of rectifiers are used as basic components within the power supply units due to their high efficiency.
- These are used to provide power to motors, LEDs, etc.
- 7

### Slide 9
- Merits of Bridge Type Full Wave Rectifier
- The efficiency of rectifying a bridge is higher when compared to a half wave rectifier.
- The ripple factor is lower which leads to a DC output waveform.
- Bridge rectifiers are a cost option as they eliminate the need, for a center tapped transformer, unlike center tapped rectifiers.
- 8

### Slide 10
- Dem
- erits of Bridge Type Full Wave Rectifier
- Setting up bridge rectifiers involves a circuit arrangement, which might pose challenges for those who are new to electronics.
- The components used in bridge rectifiers such as diodes can be more expensive compared to rectification methods.
- Multiple diodes in bridge rectifiers can generate heat so it's important to include heat dissipation solutions like heat sinks.
- 9

### Slide 11
- Applications of Bridge Type Rectifier
- Power Supply Circuits.
- Battery
- Charging
- .
- DC
- Motor
- Drives.
- LED
- Lighting
- .
- Welding
- Machines.
- Power
- Inverters
- .
- Solar Power
- Systems
- .
- 10

### Slide 12
- Comparison Between Half Wave & Full Wave Rectifier
- 11
- Parameter
- Half Wave Rectifier
- Full Wave Rectifier
- Number of diodes required
- Requires only one diode.
- Center-tapped FWR requires two diodes.
- Bridge FWR requires 4 diodes.
- Rectified cycles of AC
- In half wave rectifier, only half cycle of AC.
- Full wave rectifier rectifies the both positive and negative cycles of AC
- Maximum efficiency of rectification
- 40.6%
- 81.2%.
- Ripple factor
- 1.21
- 0.482
- Form factor
- 1.57
- 1.11
- Average output current
- lav
- =
- lm
- /
- π
- lav
- =2lm/
- π

### Slide 13
- Comparison Between Bridge & Centre Tapped Rectifier
- 12
- Parameter
- Centre-Tapped Rectifier
- Bridge Rectifier
- Number of diodes required
- Center-tapped FWR requires two diodes.
- Bridge FWR requires 4 diodes.
- Circuit complexity
- The circuit of a
- centre
- -tapped rectifier is less complicated.
- The circuit of a bridge rectifier is more complex than that of the
- centre
- tapped rectifier.
- Rating of transformer
- kVA
- Smaller than that of a
- centre
- -tapped rectifier.
- Voltage regulation
- Better voltage regulation
- Good voltage regulation
- Peak inverse voltage (PIV)
- 2Vsmax
- Vsmax
- Transformer utilization factor
- 0.692
- 0.8106

### Slide 14
- Summary of the Lecture
- 1. We have studied about merits and demerits of half wave and full wave rectifier.
- 2. We have illustrated about applications of both type of rectifiers.
- 3. We have studied about comparison between half wave and full wave rectifier.
- 13

### Slide 15
- Next
- Topic
- Numerical Based On rectifiers
- 14

### Slide 16
- Quiz/ FAQ’s
- Q.1: How full wave rectifier is better than half wave rectifier?
- Q.2:
- Explain difference between half wave and full wave rectifier.
- Q.3: What are applications of half wave and full wave rectifier?
- 1
- 5

### Slide 17
- R
- eferences/ Articles/ Videos
- https://www.tutorialspoint.com/difference-between-centre-tapped-rectifier-and-bridge-rectifier
- https://www.rfwireless-world.com/terminology/rf-components/half-wave-vs-full-wave-rectifiers
- https://www.rohm.com/electronics-basics/ac-dc-converters/acdc_what2
- 1
- 6

### Slide 18
- Faculty-curated videos, NPTEL, Coursera, LinkedIn, or other relevant learning resources
- https://www.coursera.org/learn/modeling-and-control-of-single-phase-rectifiers-and-inverters
- https://nptel.ac.in/courses/117108124
- 17

### Slide 19
- Class-Wise
- Feedback
- Faculty members are encouraged to generate a class specific QR code at the end of each session to collect brief student feedback. This can support self-reflection, improve teaching practices, and allow students to share insights, suggestions, or concerns anonymously.
- 18

### Slide 20
- Thank You
- For queries
- Email: akhilnigam.eee@cumail.in
- 19


## 1.2.5
### Slide 1
- UNIVERSITY INSTITUTE OF ENGINEERING
- ENGINEERING FOUNDATION-[EF1-EF5]
- PROGRAME NAME: BE CSE
- ALL BRANCHES/1st
- SEMICONDUCTOR PHYSICS AND APPLICATIONS
- (26SPH-143)
- Unit No.  1                    Chapter No.2	Lecture No.10
- Topic :Numerical Based On rectifiers
- Faculty Name and
- E_Code
- : Dr. Akhil[E7113]    Designation: Associate Professor
- Academic Session 2026-27
- ODD Semester Jul-Dec 2026

### Slide 2
- Learning Objectives
- Students will be able to understand basic concepts of rectifiers.
- Students will be able to determine unknown parameters of rectifier.
- Students will be able
- to analyze operation of both half wave and
- ful
- wave rectifier.
- 1

### Slide 3
- Recap of Previous Lecture
- If the lecture is in continuity, then list down the topics covered in the previous lecture.
- Merits and demerits of half wave rectifier, merits and demerits of full wave rectifier
- , comparison  between half wave and full wave rectifier.
- 2

### Slide 4
- Numerical Problem-1
- An AC voltage of peak value 𝑉𝑚=20V is applied to a half-wave rectifier. Calculate the average (DC) output voltage.
- 3

### Slide 5
- Numerical Problem-2
- If the peak voltage of the AC supply is 25 V, calculate the RMS output voltage of the half-wave rectifier.
- 4

### Slide 6
- Numerical Problem-3
- The applied input
- a.c.
- power to a half-wave rectifier is 100 watts. The
- d.c.
- output power obtained is 40 watts.
- (
- i
- ) What is the rectification efficiency ?
- 5

### Slide 7
- Numerical Problem-4
- A half-wave rectifier is supplied by 18 V RMS AC. Find the DC output voltage.
- 6

### Slide 8
- Numerical Problem-5
- Consider half wave rectifier is working on 200V (RMS Value) input voltage, 50 Hz AC power supply. Then analyze its DC output voltage, RMS output voltage and peak inverse voltage.
- 7

### Slide 9
- Summary of the Lecture
- 1. We have studied about numerical problems of half wave rectifier.
- 2.
- We have studied about numerical problems of full wave rectifier.
- 8

### Slide 10
- Next
- Topic
- Introduction, Transistor Terminals, Transistor Action
- 9

### Slide 11
- Quiz/ FAQ’s
- Q.1: How full wave rectifier is better than half wave rectifier?
- Q.2:
- Explain difference between half wave and full wave rectifier.
- Q.3: What are applications of half wave and full wave rectifier?
- 1
- 0

### Slide 12
- R
- eferences/ Articles/ Videos
- https://www.tutorialspoint.com/difference-between-centre-tapped-rectifier-and-bridge-rectifier
- https://www.rfwireless-world.com/terminology/rf-components/half-wave-vs-full-wave-rectifiers
- https://www.rohm.com/electronics-basics/ac-dc-converters/acdc_what2
- 1
- 1

### Slide 13
- Faculty-curated videos, NPTEL, Coursera, LinkedIn, or other relevant learning resources
- https://www.coursera.org/learn/modeling-and-control-of-single-phase-rectifiers-and-inverters
- https://nptel.ac.in/courses/117108124
- 12

### Slide 14
- Class-Wise
- Feedback
- Faculty members are encouraged to generate a class specific QR code at the end of each session to collect brief student feedback. This can support self-reflection, improve teaching practices, and allow students to share insights, suggestions, or concerns anonymously.
- 13

### Slide 15
- Thank You
- For queries
- Email: akhilnigam.eee@cumail.in
- 14


---
