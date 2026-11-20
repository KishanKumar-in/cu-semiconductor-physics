# Chapter 2.2 - Complete Study Material


## 📘 LECTURE NOTES & EXPLANATIONS


### Lecture Topic 2.2.1
# Lecture Topic 2.2.1

## CO.1  Describe the properties of materials and the applications of semiconductor electronic devices such as diodes and transistors.

Introduction to energy storage devices and its classifications:

Battery:

A battery is a device that stores chemical energy and converts it into electrical energy to power electrical devices.

It has two terminals: positive (+) and negative (−).

Inside, a chemical reaction happens that pushes electrons through a wire from the negative to the positive terminal.

This flow of electrons is what we call electric current.

Fig.1 Battery

## Types of Batteries:

Primary batteries – used once (e.g., AA batteries in a clock).

Secondary batteries – rechargeable (e.g., mobile phone battery).

Primary batteries are disposable, non-rechargeable devices. They must be replaced once their energy supply is depleted.

Secondary or rechargeable batteries contain active materials that can be regenerated. When the energy produced by these industrial batteries drops below optimum efficiency, they may be recharged according to various methods, depending on the battery construction. Secondary batteries are useful in applications where frequently replacing disposable batteries is more costly, such as in electric vehicles, handheld power tools and automobile starters.

Energy Storage Devices:

- Capacitor

- Batteries

- Fossil fuel storage

- Flywheel energy storage

- Superconducting magnetic energy storage

- Compressed air energy storage

- Cryogenic energy storage

- Pumped storage hydraulic electricity

01. Capacitor

It is the device that stores the energy in the form of electrical charges, these charges will be accumulated on the plates. It will store the energy as it can store charges with the number of charges on the capacitor, as it stores the charges and charging & discharging take place.

When the switch is connected, it starts to store the energy but when the switch is off it discharges the charges such that the device will be on even when the device will be off. Here when the charged capacitor is disconnected from the switch then energy remains in the field in the space between its plates. This will pass all the alternating currents without passing direct currents. here if we see the difference between battery and capacitor then the battery will convert the chemical energy into electrical energy and the capacitor stores energy physically, in a form very much like static energy.

02. Batteries

The battery is an energy storage device that enables energy from renewable resources like solar and wind to be stored and released when the customer is in need. It is possible to store the energy in the form of the electrochemical present in that which will convert chemical energy into electrical energy. This electrochemical cell has an anode and cathode where the positive terminal is the cathode and the negative terminal is the anode, these are found in many devices such as phones, television remote controllers, electric cars.

03. Fossil Fuel Storage

Here energy is stored in fossil fuels. the renewable resources will store the energy and this energy is liberated when it is used as fossil fuels. Fossils such as coal and gasoline will store the energy that will be released from renewable resources like sunlight will be taken and further, when it has died it will be buried for a longer period. Later when it is converted into fuel then it is used as energy for many purposes.

04. Flywheel Energy Storage

It is a device that works by accelerating the rotor to a very high speed. It will maintain the energy in the form of rotation called rotational energy. When there will be energy extraction of the system the rotational speed of the flywheel is reduced as a consequence of the principle of conservation of energy.

05. Superconducting Magnetic Energy Storage

It is system storage energy that is developed such that it stores the energy in the form of the magnetic field that is created by the flow of direct current in the superconducting coil that is cooled below the superconducting critical temperature.

This energy storage includes three parts: one is the superconducting coil, the second is the power conducting system, and the cryogenically cooled refrigerator. Here shortly once the superconducting is charged the current will not be released and magnetic energy is stored indefinitely. This stored energy is released back to the network by discharging the coil.

06. Compressed Air Energy Storage

The energy is produced by using compressed air. In this storage, constant volume and constant pressure are stored. Here if we see the working when the air is trapped and compressed such that it produces the heat thus by producing the energy. It is the way where the energy is generated at one time and released at another time.

The energy generated during this will meet lower energy demand but also can meet higher energy demand. This CAES system stores the energy by using off-peak electricity by compressing the air and stored it in a reservoir.

07. Pumped Storage Hydraulic Electricity

It is a device that uses water reservoirs as a resource so it is called a hydroelectric storage device. It is a configuration of two water reservoirs at different elevations that generate power as water moves from one to another side while passing through the turbine. It converts and stores mechanical energy into electrical energy. This system requires power as the water moves from the upper reservoir. It is quite similar to the giant battery which stores the energy and is released whenever it is needed. There are two types of storage hydro-powers:

Relevant Video links for this lecture topic:

- Relevant Books readings (Web Links / Web Links of PDFs) for this lecture topic: https://iesd.in/page/battery-and-energy-storage-technologies

- Any web-link to be attached relevant to the topic: https://www.globalspec.com/learnmore/electrical_electronic_components/batteries/batteries

---


### Lecture Topic 2.2.2
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

---


### Lecture Topic 2.2.3
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

---


### Lecture Topic 2.2.4
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

---


## 🖥️ PRESENTATION SLIDES


# Chapter 2.2 - All Lecture Slides Text


## 2.2.1
### Slide 1
- UNIVERSITY INSTITUTE OF ENGINEERING
- ENGINEERING FOUNDATION-[EF1-EF5]
- PROGRAME NAME: BE CSE
- ALL BRANCHES/1st
- SEMICONDUCTOR PHYSICS AND APPLICATIONS
- (26SPH-143)
- Unit No. 2                 Chapter No.4	Lecture No.17
- Topic :Introduction to energy storage devices and its classifications
- Faculty Name and
- E_Code
- : Dr. Akhil[E7113]    Designation: Associate Professor
- Academic Session 2026-27
- ODD Semester Jul-Dec 2026

### Slide 2
- Learning Objectives
- Students will be able to understand energy storage devices.
- Students will be able to analyze different components of energy storage devices.
- Students will be able
- to explain working of energy storage devices.
- 1

### Slide 3
- Recap of Previous Lecture
- Transistor as a switch and an Amplifier.
- 2

### Slide 4
- Energy Storage Devices
- Energy storage can be defined as the process in which we store the energy that was produced all at once. This process helps in maintaining the balance of the supply and demand of energy.
- Figure-1 : Energy Storage Devices
- [https://circuitglobe.com/transistor-as-an-amplifier.html]
- 3
- Additional / Recommended Readings:
- https://www.geeksforgeeks.org/transistor-as-a-switch/

### Slide 5
- Energy Storage Devices
- These storages can be of any type according to the shelf-life of energy which means some storages can store energy for a short time and some can for a long time.
- There are various examples of energy storage including a battery, flywheel, solar panels, etc.
- There are various energy storage devices like thermal, mechanical, solar etc.
- 4

### Slide 6
- Thermal Energy Storage
- Thermal storage can be defined as the process of storing thermal energy storage. The process of storing thermal energy is to continuously heat and cool down the container (in which we are storing thermal energy).
- 5
- Figure-2 : Thermal Energy Storage
- [https://www.geeksforgeeks.org/energy-storage//]
- Additional / Recommended Readings:
- https://www.geeksforgeeks.org/energy-storage/

### Slide 7
- Mechanical Energy Storage
- These types of energy storage usually use kinetic energy to store energy. Here kinetic energy is of two types: gravitational and rotational.
- 6
- Figure-3 : Mechanical Energy Storage
- [https://www.geeksforgeeks.org/energy-storage//]
- Additional / Recommended Readings:
- https://www.geeksforgeeks.org/energy-storage/

### Slide 8
- Compressed Air System Storage
- These systems use compressed air to store energy for later use.
- This storage can be of any type: Diabatic, adiabatic, or isothermal.
- 7
- Figure-4 : Compressed Air System Storage
- [https://www.geeksforgeeks.org/energy-storage//]
- Additional / Recommended Readings:
- https://www.geeksforgeeks.org/energy-storage/

### Slide 9
- Electrochemical Storage
- Electrochemistry is the production of electricity through chemicals.
- This energy storage is used to view high density and power density.
- 8
- Figure-5 : Electrochemical Storage
- [https://www.geeksforgeeks.org/energy-storage//]
- Additional / Recommended Readings:
- https://www.geeksforgeeks.org/energy-storage/

### Slide 10
- Solar Energy Storage
- Storing solar energy for later use is known as solar energy storage. It can be done easily just by using sunlight.
- It uses no electricity.
- 9
- Figure-6 : Solar Energy Storage
- [https://www.geeksforgeeks.org/energy-storage//]
- Additional / Recommended Readings:
- https://www.geeksforgeeks.org/energy-storage/

### Slide 11
- Applications of Energy Storage Devices
- Solar panel
- electricity
- Electrical
- appliances
- Micro-
- grids
- Integrated
- Sensors
- Water
- heating
- Thermal power plants
- 10

### Slide 12
- Summary of the Lecture
- 1. We have studied about different energy storage devices.
- 2. We have different applications of energy storage devices.
- 3. We have studied about configuration of energy storage devices.
- 11

### Slide 13
- Next
- Topic
- Selecting Battery: Basic Battery Specifications, common parameters of battery/applications
- 12

### Slide 14
- Quiz/ FAQ’s
- Q.1: How energy storage devices perform for semiconductor material?
- Q.2: Discuss solar energy storage device with its working.
- Q.3: Explain applications of different energy storage devices.
- 1
- 3

### Slide 15
- R
- eferences/ Articles/ Videos
- https://www.geeksforgeeks.org/energy-storage/
- https://www.eetasia.com/power-electronics-based-energy-storage-devices/
- 1
- 4

### Slide 16
- Faculty-curated videos, NPTEL, Coursera, LinkedIn, or other relevant learning resources
- https://onlinecourses.nptel.ac.in/e-learning/preview/noc21_mm34
- https://onlinecourses.nptel.ac.in/noc25_ee75/preview
- 15

### Slide 17
- Class-Wise
- Feedback
- Faculty members are encouraged to generate a class specific QR code at the end of each session to collect brief student feedback. This can support self-reflection, improve teaching practices, and allow students to share insights, suggestions, or concerns anonymously.
- 16

### Slide 18
- Thank You
- For queries
- Email: akhilnigam.eee@cumail.in
- 17


## 2.2.2
### Slide 1
- UNIVERSITY INSTITUTE OF ENGINEERING
- ENGINEERING FOUNDATION-[EF1-EF5]
- PROGRAME NAME: BE CSE
- ALL BRANCHES/1st
- SEMICONDUCTOR PHYSICS AND APPLICATIONS
- (26SPH-143)
- Unit No. 2                 Chapter No.4	Lecture No.18
- Topic :Selecting Battery: Basic Battery Specifications, common parameters of battery/applications
- Faculty Name and
- E_Code
- : Dr. Akhil[E7113]    Designation: Associate Professor
- Academic Session 2026-27
- ODD Semester Jul-Dec 2026

### Slide 2
- Learning Objectives
- Students will be able to understand battery with selection parameters.
- Students will be able to analyze different specifications of battery.
- Students will be able
- to explain working of battery system.
- 1

### Slide 3
- Recap of Previous Lecture
- Introduction to energy storage devices and its classifications
- 2

### Slide 4
- Battery
- A battery is an electrochemical device that stores energy and provides electric power through a chemical reaction. It converts chemical energy into electrical energy.
- Figure-1 : Battery
- [https://circuitglobe.com/difference-between-cell-and-battery.html]
- 3
- Additional / Recommended Readings:
- https://www.globalspec.com/learnmore/electrical_electronic_components/batteries/batteries

### Slide 5
- Types of Battery
- There are various types of batteries. Based on charging capacity we can divide them in two types:
- Primary cell battery
- Secondary cell battery
- 4

### Slide 6
- Primary Battery
- Primary batteries are those batteries which are not rechargeable.
- It once charged then it can not be used further.
- 5
- Figure-2 : Thermal Energy Storage
- [https://www.geeksforgeeks.org/battery-types/
- Additional / Recommended Readings:
- https://www.geeksforgeeks.org/battery-types//

### Slide 7
- Examples of Primary Battery
- Alkaline cells:
- Alkaline cell is a type of primary cell battery where electrolyte has a PH level of above 7 and mainly potassium or sodium hydroxide is used as electrolyte. zinc and manganese dioxide is used as cathode and anode electrode.
- Aluminium
- –air battery:
- Aluminium
- –air battery is a type of disposable primary battery which produces electric power from the reaction between
- aluminium
- and the oxygen in the air. That's why it is called as
- aluminium
- -air battery.
- 6

### Slide 8
- Applications of Primary Battery
- Portable Electronics
- Medical equipment
- Toys
- Emergency backup
- Space Mission
- 7

### Slide 9
- Secondary Battery
- Secondary cell batteries are those types of battery which can be recharged after once it get discharged.
- 8
- Figure-2 : Secondary Battery
- [https://www.geeksforgeeks.org/battery-types/
- Additional / Recommended Readings:
- https://www.geeksforgeeks.org/battery-types//

### Slide 10
- Examples of Secondary Battery
- Lead Acid:
- Lead Acid battery is an example of rechargeable battery which use lead(PbSo4) as cathode anode electrode and sulfuric acid as electrolyte.
- Sodium-Ion Batteries:
- This type of battery use Sodium(Na) as their charge carrier ion.
- Lithium-ion:
- Lithium-ion battery is a type of rechargeable battery which gets charged and discharged by lithium-ion movement between positive electrode and negative electrode.
- 9

### Slide 11
- Applications of Secondary Battery
- Electronics devices:
- Secondary cell batteries are used in maximum electronics devices such as mobile phone, laptop, headphones, tablet, charging light etc.
- Transportation:
- Currently secondary batteries are used in transportation system in Electric vehicles, Hybrid electric vehicles (HEVs), Electric bikes and scooters.
- Renewable Energy Storage:
- Storing excess energy generated from solar panels and wind turbines for later use.
- 10

### Slide 12
- Parameters for Battery Selection
- Energy Density:
- Energy density is determined by comparing the potential energy available to the overall weight of the system.
- Current Availability (Power Density):
- When a device has high power density it means it can sustain high current draws for a ‘large’ period of time.
- Durability:
- Physical external factors can greatly affect the performance of your battery.
- Lifetime:
- There are two main factors to a battery’s lifetime: charge life and total life.
- 11

### Slide 13
- Specifications of Battery
- Terminal Voltage:
- The ‘nominal voltage’ is what the chemists tell us the cell should produce with zero current flowing.
- Energy Capacity:
- The energy that a cell can store depends on the chemistry and the physical size of the plates, mostly the area, but to some extent the thickness of the plates for some chemistries. It is in ampere-hours.
- State of Charge:
- The state of charge of a battery can often be determined from the condition of the electrolyte.
- 12

### Slide 14
- Summary of the Lecture
- 1. We have studied about different types of batteries.
- 2. We have different applications of
- batteries
- .
- 3. We have studied about specifications of battery.
- 13

### Slide 15
- Next
- Topic
- Power Supplies: Linear power Supply
- 14

### Slide 16
- Quiz/ FAQ’s
- Q.1: How energy can be stored in a battery?
- Q.2: Discuss specifications of batteries.
- Q.3: Explain applications of primary and secondary battery.
- 1
- 5

### Slide 17
- R
- eferences/ Articles/ Videos
- https://electricalacademia.com/batteries/battery-specifications-explained-parameters/
- https://www.geeksforgeeks.org/battery-types/
- https://www.arrow.com/en/research-and-events/articles/choosing-the-right-battery-for-your-internet-of-things-application
- 1
- 6

### Slide 18
- Faculty-curated videos, NPTEL, Coursera, LinkedIn, or other relevant learning resources
- https://onlinecourses.nptel.ac.in/e-learning/preview/noc21_mm34
- https://onlinecourses.nptel.ac.in/noc25_ee75/preview
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


## 2.2.3
### Slide 1
- UNIVERSITY INSTITUTE OF ENGINEERING
- ENGINEERING FOUNDATION-[EF1-EF5]
- PROGRAME NAME: BE CSE
- ALL BRANCHES/1st
- SEMICONDUCTOR PHYSICS AND APPLICATIONS
- (26SPH-143)
- Unit No. 2                 Chapter No.4	Lecture No.19
- Topic :Power Supplies: Linear power Supply
- Faculty Name and
- E_Code
- : Dr. Akhil[E7113]    Designation: Associate Professor
- Academic Session 2026-27
- ODD Semester Jul-Dec 2026

### Slide 2
- Learning Objectives
- Students will be able to understand linear power supply system.
- Students will be able to analyze working of linear power system.
- Students will be able
- to discuss applications of linear power supply system.
- 1

### Slide 3
- Recap of Previous Lecture
- Selecting Battery: Basic Battery Specifications, common parameters of battery/applications
- 2

### Slide 4
- Linear Power Supply System
- A linear power supply is a power supply unit (PSU) that does not contain any switching or digital components.
- Figure-1 : Block Dig. Of Linear Power Supply System
- [https://stewart-switch.com/linear-power-supply-block-diagram]
- 3
- Additional / Recommended Readings:
- https://www.circuitbread.com/ee-faq/what-are-the-efficiency-levels-of-different-power-supplies

### Slide 5
- Working of Linear Power Supply System
- 4
- Figure-2 : Working Steps Of Linear Power Supply System
- [https://stewart-switch.com/linear-power-supply-block-diagram]

### Slide 6
- Working of Linear Power Supply System
- The AC input is fed to a step-down transformer and then rectified. This rectified voltage is then fed to a filter capacitor which outputs a DC voltage with ripple. The voltage regulator block is employed to eliminate the ripple.
- This smoothed voltage is then fed across the output capacitor which further smooths the output voltage – after all this smoothing the output voltage is almost as clean as if it's from a battery.
- 5

### Slide 7
- Working of Linear Power Supply System
- The voltage regulator block consists of a pass transistor and a Zener diode. The pass transistor is always on causing a good amount of on-state voltage drop and associated power loss.
- Because of these reasons, the efficiency of the linear power supply is around 40% to 50%.
- 6

### Slide 8
- Applications of LPS
- High-end amplifiers, mixers, and DACs use linear supplies to avoid noise.
- Used in operational amplifier circuits, sensors, and signal processing.
- Transceivers, RF circuits, and oscillators need clean power.
- Used in PLC-based systems, sensors, and instrumentation where stable voltage is critical.
- 7

### Slide 9
- Summary of the Lecture
- 1. We have studied about block diagram of linear power supply.
- 2. We have analyzed working of
- linear power supply.
- 3. We have studied about specifications of linear power supply.
- 8

### Slide 10
- Next
- Topic
- Power Supplies: Switch Mode Power Supply
- 9

### Slide 11
- Quiz/ FAQ’s
- Q.1: How energy can be stored in a battery?
- Q.2: Discuss specifications of LPS.
- Q.3: Explain applications of LPS.
- 1
- 0

### Slide 12
- R
- eferences/ Articles/ Videos
- https://www.circuitbasics.com/linear-power-supplies/
- https://www.circuitbread.com/ee-faq/what-are-the-efficiency-levels-of-different-power-supplies
- 1
- 1

### Slide 13
- Faculty-curated videos, NPTEL, Coursera, LinkedIn, or other relevant learning resources
- https://elearn.nptel.ac.in/shop/completed-courses/execedu-closed/battery-cell-technology-materials-and-industrial-applications/?v=c86ee0d9d7ed
- https://onlinecourses.nptel.ac.in/noc21_mm34/preview
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


## 2.2.4
### Slide 1
- UNIVERSITY INSTITUTE OF ENGINEERING
- ENGINEERING FOUNDATION-[EF1-EF5]
- PROGRAME NAME: BE CSE
- ALL BRANCHES/1st
- SEMICONDUCTOR PHYSICS AND APPLICATIONS
- (26SPH-143)
- Unit No. 2                 Chapter No.4	Lecture No.20
- Topic : Power Supplies: Switch Mode Power Supply
- Faculty Name and
- E_Code
- : Dr. Akhil[E7113]    Designation: Associate Professor
- Academic Session 2026-27
- ODD Semester Jul-Dec 2026

### Slide 2
- Learning Objectives
- Students will be able to understand switched mode power supply system.
- Students will be able to analyze working of
- switched mode
- power system.
- Students will be able
- to discuss applications of
- switched mode
- power supply system.
- 1

### Slide 3
- Recap of Previous Lecture
- Power Supplies: Linear power Supply
- 2

### Slide 4
- Switched Mode Power Supply System
- A switched power supply is an electronic power supply that converts electric power efficiently.
- Figure-1 : Block Dig. Of Switched Mode Power Supply System
- [https://www.pocketmagic.net/simple-switched-power-supplies/]
- 3
- Additional / Recommended Readings:
- https://www.pocketmagic.net/simple-switched-power-supplies/

### Slide 5
- Working of
- Switched Mode
- Power Supply System
- 4
- Figure-2 : Working Steps Of Switched Mode Power Supply System
- [https://www.campuscomponent.com/blogs/post/how-to-build-a-switch-mode-power-supply]

### Slide 6
- Working of Switched Mode Power Supply System
- Input Stage (Stage 1)
- The AC input supply with a frequency of (50-60) Hz is directed to the rectifier and filter circuit.
- The output, characterized by various fluctuations, requires a capacitor with sufficient capacitance to handle input variations.
- The unregulated DC output is then fed into the central switching section of the SMPS for regulation; this section operates without a transformer for the step-down in input voltage supply.
- 5

### Slide 7
- Working of Switched Mode Power Supply System
- Switching Stage (Stage 2)
- Comprising fast-switching devices such as a Power transistor or a MOSFET, this section toggles ON and OFF in response to voltage variations.
- The resulting output is directed to the primary of a smaller, lighter, and highly effective transformer, facilitating voltage step-down.
- The efficiency of this transformer surpasses alternative step-down methods, contributing to a higher power conversion ratio.
- 6

### Slide 8
- Working of Switched Mode Power Supply System
- Output Stage (Stage 3)
- The output from the switching section undergoes rectification and filtering to achieve the desired DC voltage.
- The regulated output voltage is then supplied to the control circuit.
- 7

### Slide 9
- Working of Switched Mode Power Supply System
- Control Unit (Stage 4)
- The control unit is primarily focused on feedback and encompasses various sections.
- The internal control unit includes an oscillator, amplifier, sensor, etc.
- The sensor detects the output signal and provides feedback to the control unit, ensuring isolation of signals to prevent sudden spikes from affecting the circuitry.
- 8

### Slide 10
- Applications of SMPS
- Deployment in servers, power stations, and personal computers for diverse electronic applications.
- Integration into vehicles for battery charging purposes.
- Application in factories and industries to meet power requirements.
- Implementation within the railway system and security systems for efficient power management.
- 9

### Slide 11
- Summary of the Lecture
- 1. We have studied about block diagram of switched mode power supply.
- 2. We have analyzed working of
- switched mode power supply.
- 3. We have studied about specifications of switched mode power supply.
- 10

### Slide 12
- Next
- Topic
- Basic Introduction to circuits, Various Circuit Elements
- 11

### Slide 13
- Quiz/ FAQ’s
- Q.1: How energy can be stored in a battery?
- Q.2: Why is an SMPS more efficient than a linear power supply? Explain with power loss analysis.
- Q.3: Describe the operation of an SMPS during overload and short-circuit conditions.
- 1
- 2

### Slide 14
- R
- eferences/ Articles/ Videos
- https://www.campuscomponent.com/blogs/post/how-to-build-a-switch-mode-power-supply
- https://www.circuitbread.com/ee-faq/what-are-the-efficiency-levels-of-different-power-supplies
- 1
- 3

### Slide 15
- Faculty-curated videos, NPTEL, Coursera, LinkedIn, or other relevant learning resources
- https://elearn.nptel.ac.in/shop/completed-courses/execedu-closed/battery-cell-technology-materials-and-industrial-applications/?v=c86ee0d9d7ed
- https://onlinecourses.nptel.ac.in/noc21_mm34/preview
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
