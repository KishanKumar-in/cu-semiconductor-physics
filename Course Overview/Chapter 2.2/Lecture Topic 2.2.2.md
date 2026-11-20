# Lecture Topic 2.2.2

CO.3 Apply the relationships between key parameters of diodes, transistor configurations, to analyze electronic circuits.

Selecting Battery: Basic Battery Specifications, common parameters of battery/applications;

Selection of battery:

The following factors mainly influence the choice of battery chemistry for an application:

- Reusability – The very first thing that one needs to determine is whether the given circuit should be rechargeable or it should rely on battery replacement. Accordingly, primary or secondary battery types may be used for the device.

- Life Cycle Durability – The durability of a battery becomes an even more important consideration when it is the primary battery used in the circuit. Even if it is the secondary battery used in a circuit, it is important to note how long one charge-discharge cycle will sustain and what number of cycles a battery can run without damage (like swelling in case of prismatic and pouch cells). It is also important to note the duration of the charge-discharge cycle for a secondary battery to determine the charging procedure and schedule.

- Energy Density – This is the amount of energy that can be stored per unit mass or volume. Each battery-chemistry has a specific energy density which influences the size and weight of the battery. Portable devices essentially require batteries to be lightweight and compact. The non-portable applications may compromise with the weight, though still may have some size-constraint.

- Power Density – It is the maximum rate of energy discharge per unit mass or volume. Power density plays an important role in the suitability of battery chemistry for a given application. Many applications require a high discharge rate or may be susceptible to a sudden surge in power discharge. This may affect the safety of a battery. Power density is the primary performance influence of a battery in a circuit.

- Safety – The two most important factors that influence the safety of a battery are its thermal stability and power density. A battery should have enough power density to meet any possible discharge rates in a circuit. Each battery-chemistry also has specific operating temperatures. At high temperatures, battery components may breakdown and undergo exothermic reactions. The cells should be adequately spaced for better thermal stability. It may be necessary to provide mechanisms such as liquid cooling or air cooling to manage heat in a device. It is also important to note battery temperature for different discharge rates and current levels.

- Geometry and Size – Different battery chemistries are available in a variety of shapes and sizes. For a given battery chemistry, optimum shape and size of the battery should be selected such that it does not compromise the required ampere-hour capacity, life-cycle duration, size or weight restrictions, and safety. Most of the prismatic and pouch batteries are prone to swelling over extended use, so there should be sufficient space in a device to accommodate that.

- Cost – Finally, the selection of battery chemistry depends on the cost. The cost can be adjusted by selecting alternative battery chemistry or packaging. However, there should be no compromise with performance or safety for cost-cutting.

Specifications of Battery:

- Terminal Voltage – Any battery is used as a voltage source in a circuit. So, the very first specification that should be checked is the required terminal voltage. The voltage from a battery should be always regulated using a transistor circuit or voltage regulator IC to avoid any noise or fluctuations from the battery. The voltage regulator can also step down the supply voltage to the required value in the event the battery voltage is greater than the one needed in the circuit. The supply from the battery may sometimes require to be stepped up using a transistor amplifier if a higher voltage is required.

As a battery discharges, its terminal voltage starts declining, and its internal resistance starts increasing. The best way to test the state of a battery is to measure its terminal voltage without load or under load conditions.

- Discharge Rate – The discharge rate is particularly important in determining the performance of the battery in a circuit. It is also an important factor in determining the safety of a battery.

- Ampere-hour Capacity – The energy capacity of batteries is expressed as ampere-hour. Any battery can transfer a specific number of electrons to a circuit before complete discharge. This is a considerable number — It is the approximate value of continuous current that may be delivered to a circuit by the battery over a specific number of hours. If a battery has a capacity of 1 amp-hour, it means the battery can supply 1 A of continuous current for one hour or 2 A of continuous current for half an hour and so on. The ampere-hour rating gives an approximate duration as the number of hours that the battery can run before full discharge on supplying a certain amount of continuous current.

This is always an approximate value, and the battery may fully discharge before the estimated duration. For example, if a 20-ampere hour battery might be connected to a low resistive load, which may be drawing a 20A current, ideally, the battery should long for one hour. But, it may fully discharge slightly before one hour due to heating. Similarly, a battery connected to a low-power load may be estimated to last for several years. Still, it may fully discharge before the estimated duration due to life-cycle related factors like leakage current, evaporation of electrolyte, high temperatures, humidity, or deterioration of electrodes.

The amp-hour capacity of a battery is specified for a particular current. The manufacturers may also supply derating curves of capacity for different currents and temperatures. In the case of secondary batteries, the Amp-Hour rating helps in determining the procedure and schedule of charging.

Series and parallel combination of batteries

The batteries may need to be connected to form a larger bank of batteries to achieve higher voltage or current. When batteries or cells are connected in series, the current remains the same, while total voltage is the sum of voltages of all the batteries. The batteries connected in series should have the same amp-hour rating; otherwise, the battery with a lower amp-hour rating will get depleted before others, and the supply will be interrupted. The total amp-hour rating of the pack remains the same as the series connection. It only increases the voltage output of the battery pack.

When batteries or cells are connected in parallel, the voltage remains the same, while the total current is the sum of currents from individual batteries/cells. The batteries connected in parallel should have the same terminal voltage. The batteries in parallel again do not change the overall amp-hour rating and only increase the output current.

Applications of Battery:

- House

- Health Instruments

- Medical

- Logistics and construction

- Firefighting and Emergency

- Military

Relevant Video links for this lecture topic:

- Relevant Books readings (Web Links / Web Links of PDFs) for this lecture topic: https://analogcircuitdesign.com/switch-mode-power-supply/

- Any web-link to be attached relevant to the topic: https://www.circuitbasics.com/linear-power-supplies/