# Lecture Topic 2.1.6

CO.4 Illustrate the characteristics of diodes, different types of transistors, and the basic concepts of electric circuits.

Transistor as a switch and an Amplifier:

## Transistor as a Switch:

A transistor is a three-terminal semiconductor that regulates the current or voltage flow and acts or operates as a switch or gate for signals. The devices in the electronics and electricals are the regulated values which allows the weak signal to regulate the large amount of flow to the nozzle that regulates the flow of current. The transistors quantifies thousands and millions of transistors which are interconnected and embedded into small integrated chip or circuit boards. A transistor switch is used for opening or closing the circuit, which means we use a transistor is used as a switch in electrical devices only for low-voltage application devices due to their low power consumption. The transistors work as same as the switch when is it in cutoff and saturation regions.

## What are Transistors as a Switch?

A simple transistor is a three-terminal semiconductor which is used as an amplifier. The transistor as a switch is used for turning ON or OFF a circuit and the transistor is used as an amplifier for amplifying the current. In digital circuits, the ones and zeros are stored in the form of bits(0 or 1 ). The advantage of using the transistor as the switch is that it can control a large amount of current with a small amount of current called gain.

## Transistor as a Switch

Transistor as a switch is the simplest application of the devices. A transistor can be used for switching operations or opening or closing of the circuit. The main or basic concept of this operation relies on it's operation generally low voltage DC is on or off by the transistor in this mode. The both type of the PNP and NPM transistor are used as switches. The terminal transistor can be handled different from a single amplifier by biasing both the NPM and PNP bipolar transistor with "ON/OF" static switch. One of the basic and main use of the transistor is to transform a DC signal "ON" or "OFF" is solid state switch. Many devices such as LED's, lights requires very small milliamps logic level DC voltage and can directly driven by the output of a logic. If any circuit requires Bipolar Transistor Switch then the biasing of the transistor is either PNP or NPM which are arranged for operating the transistor for both sides of the "I-V" characteristics curves.

The operating area of the transistor switch called saturation region and the cut-off Region.

Fig.1 Transistor as switch

## Cut-off Region

In the cut-off region of the transistor, it operates under conditions of zero input base current (Ib), zero output collector current (Ic), and maximum collector voltage (Vce). This configuration creates a significant depletion layer, preventing the flow of current through the device and effectively switching it off.

- The input and base are grounded.

- Base emitter voltage Vbe<0.7v

- Base Emitter junctions is reversed.

- Base- collector junction us reversed biased.

- Transistor is "fully-Off" (cut off region)

- No collector current flows(Ic=0)

- Vout = Vcr = Vcc= 1

- Transistor operates as open switch

The cut off region of off mod when using a bipolar transistor as a switch, both junction are reverse biased Vb<0.7 and Ic=0. For PNP transistor the emitter potential must be negative with respect to base.

## Saturation Region

In this the transistor will be biased so the maximum amount of the current is applied, which results in the maximum collector current results in the minimum collector emitter voltage drop which cause in depletion layer as a small as possible and maximum current flowing through the transistor so the transistor is switched "Fully ON".

Saturation Characteristics :

- The base and input are connected to Vcc.

- Base-Emitter voltage Vbe>0.7V.

- Base-Emitter junction is forward biased.

- Base-collector junction is forward biased.

- Transistor is "fully-On"

- Max Collector current flows (Ic=Vcc/Rl)

- Vce=0 (ideal saturation)

- Vout = Vce="0".

- Transistor operates as a closed switch.

The saturation region or ON mode when use the bipolar transistor as a switch the junctions forward biased Vb>0.7v and

Ic = Maximum. In PNP transistor the emitter potential must be positive with respect to the Base. The easy way to the switch moderate to high amounts of power is to use the transistor with an open-collector output and the transistor sink an externally supplied voltage to ground thereby controlling the load connected to it.

## Transistor As An Amplifier

A transistor strengthens a weak signal by acting as an amplifier. The emitter base junction is kept in a forward biased state by the DC bias voltage provided to it. The signal's polarity has no bearing on the preservation of this forward bias. An amplifier coupled to a transistor is depicted in the figure below.

Fig.2 Transistor as amplifier

## Performance of Amplifier

In the case of common emitter configuration, we have to calculate different parameters of the Amplifier configuration. We have to calculates Voltage, Input Resistant, Output Resistant, Effective Collector load, Current Gain, Voltage Gain, Power gain, Trans Conductance.

## Input Resistance Ri

It is defined as the ratio of the negligible change in Base-Emitter voltage to the negligible in the Base Current, at constant Collector-Emitter voltage.

Input Resistance (Ri)= VBE / IB

Where,

Ri = input resistance

VBE= base-emitter voltage

IB = base current.

## Output Resistance RO

It is defined as the ratio of small change in Collector-Emitter voltage to the small change in collector current at constant base currentB.

Output resistance(RO) = ΔVCE / ΔIC

Where,

RO = output resistance

VCE = Collector Emitter Voltage

IC = Collector current

IB = Base Current

## Transistor as an Amplifier Working

When a transistor's base receives a little input signal, very little current passes between the emitter and base of the transistor. The input signal is then amplified when this low current causes a significantly higher current to flow between the emitter and collector.

The amount of amplification that a transistor can provide is determined by the bias current applied to its base. The current that flows across a transistor's base-emitter junction in the absence of an input signal is known as bias current. The greatest output signal that can be produced and the transistor's operating point are determined by the amount of bias current. The transistor can be used as a voltage amplifier or a current amplifier, depending on the type of circuit layout used. The base receives the input signal and the collector receives the output signal in a conventional emitter configuration. In this design, the transistor acts as a voltage amplifier, increasing the output signal value by amplifying the input signal voltage.

Fig.3 Operating Region of Transistor As Amplifier

Relevant Video links for this lecture topic:

- Relevant Books readings (Web Links / Web Links of PDFs) for this lecture topic: https://www.geeksforgeeks.org/transistor-as-a-switch/

- Any web-link to be attached relevant to the topic: https://www.geeksforgeeks.org/transistor-as-an-amplifier/