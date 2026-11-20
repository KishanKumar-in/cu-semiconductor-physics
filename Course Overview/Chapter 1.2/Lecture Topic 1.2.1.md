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