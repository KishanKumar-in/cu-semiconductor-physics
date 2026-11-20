# Lecture Topic 2.2.3

CO.2 Explain the characteristics and operating principles of various electronic devices including diodes and transistors.

Power Supplies: Linear power Supply:

Linear power supplies are also called linear regulators (LRs), and have numerous advantages.

A linear power supply is a device that converts high voltage AC (Alternating Current) from the main power lines to a lower AC voltage using a transformer. This is the initial step in producing a stable and clean DC (Direct Current) output, which is essential for powering sensitive electronic equipment. After the voltage reduction, the power supply uses rectifiers and filters to convert the AC into a pure form of DC, free from any significant ripples or noise.

The key advantage of a linear power supply is its ability to provide very stable and noise-free voltage, which makes it ideal for applications requiring precise voltage control, such as in audio and laboratory equipment. Despite being larger and less efficient than their switched-mode counterparts, linear power supplies are favored in settings where minimal interference is crucial, due to their simpler design and excellent voltage regulation.

## Definition and Working Principle

Welcome to the fascinating world of linear power supplies, a cornerstone in the field of electrical engineering! A linear power supply is a type of power supply that converts alternating current (AC) from the mains to a stable direct current (DC) output using a series of linear regulation techniques. Unlike their switching counterparts, linear power supplies provide a constant and noise-free output, making them ideal for sensitive electronic applications.

The working principle of a linear power supply is straightforward. It starts with a transformer that steps down the high-voltage AC from the mains to a lower voltage. This low-voltage AC is then rectified using diodes to convert it into pulsating DC. After rectification, the DC voltage is smoothed out using capacitors, creating a more stable DC voltage. Finally, a linear voltage regulator adjusts the voltage to the desired level, ensuring that the output remains constant regardless of variations in input voltage or load conditions.

Fig.1 Linear Power Supply

Transformer: The transformer steps down the high-voltage AC to a safer, lower voltage suitable for the subsequent stages. It also provides isolation from the mains supply.

Rectifier: Comprising diodes, the rectifier converts the AC voltage from the transformer into pulsating DC. Common rectifier configurations include bridge rectifiers and full-wave rectifiers.

Filter Capacitors: These capacitors smooth out the pulsating DC, reducing the ripple and creating a more stable DC output. The effectiveness of this filtering determines the quality of the DC voltage.

Voltage Regulator: The voltage regulator is the heart of the linear power supply. It ensures that the output voltage remains constant despite variations in the input voltage or the load. Common types include the 78xx series for positive voltage and the 79xx series for negative voltage.

Heat Sink: Linear regulators dissipate excess power as heat, so a heat sink is necessary to manage thermal performance and prevent overheating.

Protection Circuits: These include fuses and thermal cutoffs to protect the power supply and the connected devices from overcurrent, short circuits, and overheating.

Each of these components plays a crucial role in ensuring that the linear power supply delivers a clean, stable, and reliable DC output.

## Advantages of Linear Power Supplies

Linear power supplies offer several advantages, making them suitable for various applications despite the emergence of switching power supplies. Here are some key benefits:

Low Noise: Linear power supplies provide a very clean and noise-free output, making them ideal for audio equipment, medical devices, and other sensitive applications where electrical noise can be problematic.

Simplicity: Their design is straightforward, making them easy to understand, build, and troubleshoot. This simplicity also contributes to their reliability.

Stability: Linear power supplies deliver stable output voltage and current, which is crucial for the proper functioning of precision electronics.

Fast Transient Response: They respond quickly to changes in load conditions, maintaining stable output without significant delay.

Minimal Electromagnetic Interference (EMI): Linear power supplies generate very little EMI, which is beneficial for applications where electromagnetic compatibility is critical.

Heat Dissipation: While this can also be a drawback, the ability to dissipate heat efficiently with proper heat sinks ensures that components stay within safe operating temperatures.

These advantages highlight why linear power supplies remain a popular choice for specific applications despite the availability of more modern alternatives.

## Applications in Various Devices

Linear power supplies are used in a wide range of applications where their unique benefits are most needed. Here are some common examples:

Audio Equipment: High-fidelity audio systems, amplifiers, and other audio devices use linear power supplies to ensure low noise and high-quality sound output.

Medical Devices: Equipment such as diagnostic machines, patient monitors, and other critical medical devices rely on the clean and stable output of linear power supplies to function accurately and safely.

Laboratory Instruments: Precision instruments and measurement devices in laboratories often require the stability and low noise provided by linear power supplies.

Communication Equipment: Devices such as radios and transmitters benefit from the stable voltage and minimal interference offered by linear power supplies.

Relevant Video links for this lecture topic:

- Relevant Books readings (Web Links / Web Links of PDFs) for this lecture topic: https://www.indmall.in/faq/what-is-linear-power-supply/

- Any web-link to be attached relevant to the topic: https://www.geeksforgeeks.org/what-is-power-supply-unit-psu/