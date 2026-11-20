# Lecture Topic 2.2.4

CO.2 Explain the characteristics and operating principles of various electronic devices including diodes and transistors.

Power Supplies: Switch Mode Power Supply

A switching regulator is integrated into an electronic power supply called a switch mode power supply (SMPS), which is sometimes referred to as a switcher, switched power supply, switching-mode power supply, and simply switcher. This power supply effectively converts electrical power. An SMPS, like other kinds of power supplies, converts current and voltage characteristics while transferring power from an AC or DC source (often mains power; see AC adapter) into DC loads, like a personal computer. Switched-mode energy sources can also be significantly lighter and more compact than linear power supplies since their transformers can be considerably smaller.

This is due to the fact that, in contrast with the 50 to 60 Hz mains frequency, it works at a high rate of switching that extends from a few kHz to several MHz. The power supply architecture and the need for EMI (electromagnetic interference) suppression in commercial systems lead to a typically significantly higher component count and accompanying circuit complexity despite the smaller transformer.

## What is Switch Mode Power Supply?

A switching regulator is included in an electronic power supply called a switched-mode power supply (SMPS) to facilitate effective electrical power conversion. An SMPS converts voltage and current while transferring power to DC loads via a DC or AC source, just like other suppliers.

## Working Principle of SMPS

Switching regulators are employed in SMPS devices to maintain & regulate the output voltage by turning on or off the load current. The mean value between on and off is the appropriate power output for a system. The SMPS reduces depletion strength because, in contrast to the linear power supply, it carries transistor switches between low dissipation, full-on as well as full-off phases and spends significantly fewer seconds in high dissipation cycles.

Fig.1 SMPS Power Supply

The major components that constitute SMPS are as follows:

- Input rectifier and Filter (Diode rectifier and capacitor filter)

- High-frequency switch (Power transistor or MOSFET)

- Power transformer

- Output rectifier and Filter (Diode rectifier and capacitor filter)

- Control circuit (comparator and pulse width modulator)

Working Steps:

- In the initial stage, a rectifier and filter are used to process the AC power that comes in into DC.

- Because the SMPS operates at high frequencies, the DC signal is processed by a high-frequency switch to produce a medium-frequency pulsating DC signal.

- A power transformer reduces the high-voltage DC output to the proper level of DC signal.

- Reversing and filtering the stepped-down DC signal results in a constant steady DV output.

- To guarantee a constant output stream of the intended voltage, the control circuitry continuously monitors the generated voltage and modifies the high-frequency switch.

## Advantages

- It is highly efficient than linear power supplies. Typically, the efficiency of SMPS lies between 60% – 95%.

- Due to the high-frequency operation of the device, the overall size is small and less bulky. Thus, is compact.

- It is inexpensive because heat dissipation is less.

- The obtained output voltage can be more or less than the supply input.

## Disadvantages

- The transient spike generation due to switching action is one of the major issues. This may lead to cause RF interference thus, isolation is mandatory.

- The circuit is complex. Also, voltage regulation (controlling) is tricky.

- Proper filtration is necessary to deal with noise and spikes.

## Applications of SMPS

The devices invented under the latest technologies require a highly efficient power supply which is offered by SMPS. Thus, it finds applications in various power amplifiers, personal computers, security and railway systems, television sets, motor drives, etc.

Relevant Video links for this lecture topic:

- Relevant Books readings (Web Links / Web Links of PDFs) for this lecture topic: https://www.electronics-tutorials.ws/power/switch-mode-power-supply.html

- Any web-link to be attached relevant to the topic: https://www.geeksforgeeks.org/working-principle-of-smps/