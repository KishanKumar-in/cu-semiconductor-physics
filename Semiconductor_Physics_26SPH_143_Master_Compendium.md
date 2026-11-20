# SEMICONDUCTOR PHYSICS AND APPLICATIONS (CONT_26SPH-143)
## Master Examination Definition & Formula Compendium — Units 1, 2 and 3

**Course:** Semiconductor Physics and Applications (`CONT_26SPH-143`)  
**University:** Chandigarh University  
**Source Repository:** [`KishanKumar-in/cu-semiconductor-physics`](https://github.com/KishanKumar-in/cu-semiconductor-physics)  
**Coverage:** Strictly based on repository course material across Units 1, 2, and 3.

---

### EXAMINER'S COVERAGE & METHODOLOGY NOTE

- **[DIRECTLY IN NOTES]**: The concept is explicitly present in the CU repository lecture notes and slides.
- **[RESTORED STANDARD EQUATION]**: The lecture notes or extracted slides refer to the concept, but the mathematical expression was missing or incomplete in slide images. Standard textbook expressions are supplied.
- **[EXAM SUPPORT]**: Standard derivations, calculations, and numericals added to make repository topics immediately usable for exam preparation.
- **⚠ Examiner’s flag**: Critical corrections or clarifications where repository wording is misleading, ambiguous, or incomplete.

---

# UNIT 1: SEMICONDUCTOR FUNDAMENTALS, DIODES AND RECTIFIERS

## Chapter 1.1: Semiconductor materials and charge carriers


### 1.1.1 Semiconductor

Definition [DIRECTLY IN NOTES]:
A semiconductor is a material whose electrical conductivity lies between that of a conductor and an insulator. Its conductivity can be controlled by temperature, doping and externally applied electric fields.
Examples:
Silicon (Si)
Germanium (Ge)
Important properties
Conductivity is between conductors and insulators.
Conductivity generally increases with temperature.
Conductivity can be controlled by adding impurities.
Current conduction occurs through electrons and holes.
Semiconductors are used in diodes, transistors, integrated circuits and sensors.
Temperature coefficient of resistance (TCR):
For semiconductors, resistance generally decreases as temperature increases.
\[ \alpha_T=\frac{1}{R}\frac{dR}{dT} \]
Where:
\(\alpha_T\) = temperature coefficient of resistance, K\(^{-1}\)
\(R\) = resistance, \(\Omega\)
\(T\) = absolute temperature, K
For the usual semiconductor temperature range, \(\alpha_T\) is negative.
⚠ Examiner’s flag: The repository says that intrinsic semiconductor conductivity is zero at ambient temperature. This is not correct. An intrinsic semiconductor has a finite concentration of thermally generated charge carriers at temperatures above absolute zero. Its conductivity is small, not zero.

### 1.1.2 Intrinsic semiconductor

Definition [DIRECTLY IN NOTES]:
An intrinsic semiconductor is a chemically pure semiconductor without intentionally added impurity atoms.
Examples: pure silicon and pure germanium.
Working mechanism
At very low temperature, nearly all electrons occupy the valence band.
When thermal energy is supplied, some electrons gain sufficient energy to enter the conduction band.
Each electron leaving the valence band creates a hole.
Electrons and holes both contribute to electrical conduction.
For an intrinsic semiconductor:
\[ n=p=n_i \]
Where:
\(n\) = electron concentration, m\(^{-3}\)
\(p\) = hole concentration, m\(^{-3}\)
\(n_i\) = intrinsic carrier concentration, m\(^{-3}\)
[RESTORED STANDARD EQUATION] Intrinsic carrier concentration
\[ n_i=\sqrt{N_C N_V} \exp\left(-\frac{E_g}{2k_BT}\right) \]
Where:
\(N_C\) = effective density of states in conduction band, m\(^{-3}\)
\(N_V\) = effective density of states in valence band, m\(^{-3}\)
\(E_g\) = energy band gap, J
\(k_B\) = Boltzmann constant, J K\(^{-1}\)
\(T\) = absolute temperature, K

### 1.1.3 Extrinsic semiconductor

Definition [DIRECTLY IN NOTES]:
An extrinsic semiconductor is formed by adding a controlled quantity of impurity atoms to a pure semiconductor to increase or modify its conductivity.
The process is called doping.
Two types:
Property
N-type
P-type
Dopant
Pentavalent
Trivalent
Example
Phosphorus, arsenic
Boron, gallium
Impurity role
Donor
Acceptor
Majority carrier
Electron
Hole
Minority carrier
Hole
Electron
N-type semiconductor
Pentavalent impurity atoms have five valence electrons.
Four electrons form covalent bonds with neighbouring silicon atoms.
The fifth electron is weakly bound and can become a free electron.
Electrons are majority carriers.
P-type semiconductor
Trivalent impurity atoms have three valence electrons.
One bond remains incomplete.
The vacancy behaves as a hole.
Holes are majority carriers.
Important equations [RESTORED STANDARD EQUATIONS]
Mass-action law:
\[ np=n_i^2 \]
For an N-type semiconductor, when donor concentration is much greater than intrinsic concentration:
\[ n\approx N_D \]
\[ p=\frac{n_i^2}{n} \]
For a P-type semiconductor:
\[ p\approx N_A \]
\[ n=\frac{n_i^2}{p} \]
Where:
\(N_D\) = donor concentration, m\(^{-3}\)
\(N_A\) = acceptor concentration, m\(^{-3}\)

### 1.1.4 Energy bands and Fermi level

The repository discusses energy bands in its semiconductor explanation. The following equations restore the standard mathematical treatment.
Valence band: The highest energy band normally occupied by electrons at low temperature.
Conduction band: The energy band in which electrons are sufficiently free to contribute to conduction.
Forbidden energy gap: The energy interval between the valence-band maximum and conduction-band minimum.
\[ E_g=E_C-E_V \]
Where:
\(E_g\) = band-gap energy, J or eV
\(E_C\) = conduction-band edge energy
\(E_V\) = valence-band edge energy
Fermi level: The electron chemical potential. At thermal equilibrium, it determines the occupation probability of available energy states.
[RESTORED STANDARD EQUATION] Fermi-Dirac distribution
\[ f(E)=\frac{1}{1+\exp\left(\frac{E-E_F}{k_BT}\right)} \]
Where:
\(f(E)\) = probability that a state of energy \(E\) is occupied
\(E_F\) = Fermi energy, J
\(k_B\) = Boltzmann constant, J K\(^{-1}\)
\(T\) = temperature, K
For a non-degenerate intrinsic semiconductor:
\[ E_F\approx\frac{E_C+E_V}{2} \]
This is an approximation. The exact intrinsic Fermi level can be slightly displaced from the middle of the band gap.

### 1.1.5 Charge carriers

Electron: A negatively charged particle that can move through the conduction band.
Hole: The absence of an electron in a covalent bond or valence-band state. It behaves as a positive charge carrier.
Majority carriers: The more numerous charge carriers in a doped semiconductor.
Minority carriers: The less numerous charge carriers.
Generation: Creation of an electron-hole pair.
Recombination: An electron loses energy and fills a hole, eliminating the electron-hole pair.
Drift: Carrier movement due to an electric field.
Diffusion: Carrier movement from a region of higher concentration to lower concentration.
[RESTORED STANDARD EQUATIONS]
Drift current density:
\[ J_{n,\text{drift}}=qn\mu_n E \]
\[ J_{p,\text{drift}}=qp\mu_p E \]
Diffusion current density:
\[ J_{n,\text{diff}}=qD_n\frac{dn}{dx} \]
\[ J_{p,\text{diff}}=-qD_p\frac{dp}{dx} \]
Where:
\(J\) = current density, A m\(^{-2}\)
\(q\) = elementary charge, C
\(n,p\) = carrier concentrations, m\(^{-3}\)
\(\mu_n,\mu_p\) = carrier mobilities, m\(^2\) V\(^{-1}\) s\(^{-1}\)
\(E\) = electric field, V m\(^{-1}\)
\(D_n,D_p\) = diffusion coefficients, m\(^2\) s\(^{-1}\)
Einstein relation:
\[ \frac{D_n}{\mu_n}=\frac{D_p}{\mu_p}=\frac{k_BT}{q} \]
This is the standard non-degenerate semiconductor relation at thermal equilibrium.

## Chapter 1.2: P-N junction diode


### 1.2.1 Definition

[DIRECTLY IN NOTES]
A P-N junction is formed when P-type and N-type semiconductor regions are joined in a single semiconductor crystal.
A P-N junction diode is a two-terminal semiconductor device that allows current to flow readily in one direction and opposes it in the opposite direction.

### 1.2.2 Formation of P-N junction

When P-type and N-type regions are joined:
Electrons diffuse from the N-side towards the P-side.
Holes diffuse from the P-side towards the N-side.
Electrons and holes recombine near the junction.
Fixed ionized donor and acceptor atoms remain near the junction.
A depletion region forms.
An internal electric field and potential barrier are established.
Depletion region: The region around the junction that is depleted of mobile majority carriers.
Barrier potential: The built-in potential that opposes further majority-carrier diffusion.

### 1.2.3 Forward bias

Definition [DIRECTLY IN NOTES]:
A P-N junction is forward biased when:
P-side is connected to the positive terminal.
N-side is connected to the negative terminal.
Working
Applied voltage opposes the built-in electric field.
The potential barrier decreases.
Depletion-region width decreases.
Majority carriers cross the junction.
Forward current increases.
Approximate practical forward voltage:
Silicon: about 0.7 V
Germanium: about 0.3 V
These are approximate values, not fixed universal thresholds.

### 1.2.4 Reverse bias

A P-N junction is reverse biased when:
P-side is connected to the negative terminal.
N-side is connected to the positive terminal.
Working
Applied voltage supports the built-in electric field.
The potential barrier increases.
Depletion-region width increases.
Majority-carrier conduction is strongly suppressed.
A small minority-carrier reverse current flows.

### 1.2.5 V-I characteristics

The V-I characteristic is the graph of diode current against diode voltage.
Forward region
Current is initially small.
After the knee region, current increases rapidly.
The diode has relatively low dynamic resistance when strongly conducting.
Reverse region
A small reverse saturation current flows.
At sufficiently high reverse voltage, breakdown occurs.
Current rises sharply.
[RESTORED STANDARD EQUATION] Shockley diode equation
\[ I=I_S\left[\exp\left(\frac{V_D}{\eta V_T}\right)-1\right] \]
Where:
\(I\) = diode current, A
\(I_S\) = reverse saturation current, A
\(V_D\) = diode voltage, V
\(\eta\) = ideality factor, dimensionless
\(V_T\) = thermal voltage, V
\[ V_T=\frac{k_BT}{q} \]
At room temperature, \(V_T\) is approximately 25.9 mV.
Diode resistance
Static resistance:
\[ R_D=\frac{V_D}{I_D} \]
Dynamic resistance:
\[ r_d=\frac{dV_D}{dI_D} \]
For the ideal exponential diode in forward conduction:
\[ r_d\approx\frac{\eta V_T}{I_D} \]

### 1.2.6 Breakdown mechanisms

Zener breakdown
Occurs in a heavily doped junction.
Depletion layer is thin.
Strong electric field causes quantum-mechanical tunnelling.
Typically associated with relatively low breakdown voltages.
Avalanche breakdown
Occurs through impact ionization.
Carriers gain kinetic energy from the electric field.
They collide with atoms and create additional electron-hole pairs.
This multiplication produces a large reverse current.
Zener breakdown
Avalanche breakdown
Heavy doping
Relatively lighter doping
Thin depletion layer
Wider depletion layer
Strong electric field
Carrier impact ionization
Tunnelling mechanism
Collision and carrier multiplication
⚠ Examiner’s flag: Breakdown does not automatically destroy a diode. A properly designed diode can operate in breakdown if current and power are limited. An ordinary diode may be damaged if its reverse current exceeds its ratings.

## Chapter 1.3: Zener diode

Definition
[DIRECTLY IN NOTES]
A Zener diode is a specially designed, heavily doped P-N junction diode intended to operate in reverse breakdown.
Construction and working
The junction is heavily doped.
The depletion region is thin.
It is connected in reverse bias for voltage regulation.
When reverse voltage reaches the Zener breakdown voltage, current increases sharply.
The voltage across the diode remains approximately constant over its intended operating-current range.
Zener voltage regulation
A Zener diode is connected in parallel with the load. A series resistor limits current.
\[ I_S=I_L+I_Z \]
\[ I_S=\frac{V_{in}-V_Z}{R_S} \]
\[ I_L=\frac{V_Z}{R_L} \]
\[ I_Z=I_S-I_L \]
Where:
\(V_{in}\) = input voltage, V
\(V_Z\) = Zener voltage, V
\(R_S\) = series resistance, \(\Omega\)
\(R_L\) = load resistance, \(\Omega\)
\(I_S\) = series current, A
\(I_L\) = load current, A
\(I_Z\) = Zener current, A
Zener power:
\[ P_Z=V_ZI_Z \]
Series-resistor power:
\[ P_{R_S}=I_S^2R_S \]
Conditions for regulation
\[ I_{Z(\min)}\leq I_Z\leq I_{Z(\max)} \]
The Zener must remain within its specified current and power ratings.
Applications [DIRECTLY IN NOTES]
Voltage regulation
Over-voltage protection
Clipping circuits
Voltage shifting
Meter protection
DC power supplies
Limitations
Limited current-handling capacity.
Output voltage changes slightly with Zener current due to dynamic resistance.
Power dissipation limits its use.
Less efficient than some modern regulation methods for high-current loads.

## Chapter 1.4: Rectifiers


### 1.4.1 Rectifier definition

[DIRECTLY IN NOTES]
A rectifier is an electronic circuit that converts alternating current into unidirectional or pulsating direct current.
Rectification: The process of converting AC into pulsating DC.
Important terms
AC: Current or voltage that periodically changes magnitude and direction or polarity.
DC: Current that flows in one direction.
Load resistance: Resistance connected to the rectifier output.
Peak voltage: Maximum instantaneous voltage.
Average voltage: Mean output voltage over the specified interval.
RMS voltage: Effective value that produces the same heating effect as DC.
PIV: Peak inverse voltage, the maximum reverse voltage a diode must withstand.
Ripple: Residual AC variation present in a rectified DC output.
Ripple factor: Ratio of RMS ripple voltage to DC output voltage.

### 1.4.2 Half-wave rectifier

Definition [DIRECTLY IN NOTES]:
A half-wave rectifier uses one diode to pass one half-cycle of AC and block the other half-cycle.
Construction
One P-N junction diode
AC source or transformer secondary
Load resistance \(R_L\)
Working
Positive half-cycle:
Diode is forward biased.
Current flows through the load.
Output follows the positive half-cycle, subject to diode drop.
Negative half-cycle:
Diode is reverse biased.
Current is approximately zero.
Output is approximately zero.
Output: Pulsating DC.
[Half-Wave Diode Rectifier Circuit Explained](https://images.openai.com/static-rsc-4/mMYnObcCBzNn8whdCIO3jQDPoIe9xS9b3GL29XDRNM1nPa6K_hDbWK4CmGKQzE1lcA9CfV6JqCOSp3yRKutcsJBhfa3rPkWau-fPA32KXR85sctYMQW945uGM8UKqCJjlzuACMPGWCk0fPtWPBk_lanLQCCLeLQD27Pb-lIO744?purpose=inline)
[engineeringdevotion.com](https://www.engineeringdevotion.com/electronic-devices/lecture/half-wave-diode-rectifier.html?utm_source=chatgpt.com)
[RESTORED STANDARD EQUATIONS] Half-wave rectifier analysis
Let:
\[ v_s=V_m\sin\omega t \]
For an ideal diode:
\[ V_{DC}=\frac{V_m}{\pi} \]
\[ I_{DC}=\frac{I_m}{\pi} \]
\[ V_{RMS}=\frac{V_m}{2} \]
\[ I_{RMS}=\frac{I_m}{2} \]
Where:
\(V_m\) = peak input voltage, V
\(I_m\) = peak load current, A
\(V_{DC}\) = average output voltage, V
\(I_{DC}\) = average load current, A
\(V_{RMS}\) = RMS output voltage, V
\(I_{RMS}\) = RMS load current, A
For a resistive load:
\[ I_m=\frac{V_m}{R_L} \]
Ripple factor
\[ r=\sqrt{\left(\frac{I_{RMS}}{I_{DC}}\right)^2-1} \]
For an ideal half-wave rectifier:
\[ r=1.21 \]
Rectification efficiency
\[ \eta=\frac{P_{DC}}{P_{AC}}\times100\% \]
For an ideal half-wave rectifier:
\[ \eta_{\max}=40.6\% \]
PIV
\[ PIV=V_m \]
Ripple frequency
\[ f_r=f \]
Where \(f\) is the AC supply frequency in Hz.

### 1.4.3 Full-wave rectifier

Definition [DIRECTLY IN NOTES]:
A full-wave rectifier converts both half-cycles of an AC input into output current flowing in the same direction through the load.
Two types:
Centre-tapped full-wave rectifier.
Bridge rectifier.
General working
During the positive half-cycle, one path of diode conduction is established.
During the negative half-cycle, another diode path conducts.
Load current maintains the same direction.
The output ripple frequency is twice the input frequency.
[RESTORED STANDARD EQUATIONS] Ideal full-wave rectifier
\[ V_{DC}=\frac{2V_m}{\pi} \]
\[ I_{DC}=\frac{2I_m}{\pi} \]
\[ V_{RMS}=\frac{V_m}{\sqrt{2}} \]
\[ I_{RMS}=\frac{I_m}{\sqrt{2}} \]
Ripple factor:
\[ r=0.482 \]
Maximum rectification efficiency:
\[ \eta_{\max}=81.2\% \]
Ripple frequency:
\[ f_r=2f \]

### 1.4.4 Centre-tapped full-wave rectifier

Definition [DIRECTLY IN NOTES]:
A centre-tapped full-wave rectifier uses a centre-tapped transformer secondary and two diodes to rectify both half-cycles.
Construction
Centre-tapped transformer
Two diodes
Load resistance
Working
Positive half-cycle:
One end of the secondary is positive relative to the centre tap.
The corresponding diode conducts.
Current passes through the load.
Negative half-cycle:
The other end becomes positive relative to the centre tap.
The other diode conducts.
Load current still flows in the same direction.
[Center Tapped Full Wave Rectifier Operation](https://images.openai.com/static-rsc-4/jEaa9UUxazmfkTGdeJ3sYGHdCuT5VJabyUcEabikXih5cOaJaaJyBEMOZ12JVUCgpEi6rbZSYUHmyL2NsgKN7M1GtNNyWlwpz3YkFa-VFzJUD92HORfJYN1nX26Vt3liiYAAR3SB24fytGqj9YXlyMtcA-9Xx15cyNtmW2NxEoQ?purpose=inline)
[in.pinterest.com](https://in.pinterest.com/pin/center-tapped-full-wave-rectifier-operation--184436547230457747/?utm_source=chatgpt.com)
PIV
\[ PIV=2V_m \]
Here \(V_m\) is the peak voltage of one half of the centre-tapped secondary.

### 1.4.5 Bridge rectifier

Definition [DIRECTLY IN NOTES]:
A bridge rectifier uses four diodes arranged in a bridge so that both half-cycles produce load current in the same direction.
Working
During one half-cycle, one diagonal pair of diodes conducts.
During the other half-cycle, the opposite diagonal pair conducts.
The load-current direction remains unchanged.
[Bridge Rectifier Circuit - Electronics Basics - The Geek Pub](https://images.openai.com/static-rsc-4/gV46s6IpZGzXDNfDde-nPLZ7neS9mfjSygkU2Wx-9SiGZ9cFmiMEvLqUWDTsQr2bRYMYP7lzhrPfc_OzGZiEkpTQfp-mdLKWdlEv3-fCfqyieV6059VciwWYD5mVjkrRyXduT-siFgjITNBZaXUqqCQdBnY_zlMrcAGffbKraGw?purpose=inline)
[thegeekpub.com](https://www.thegeekpub.com/243767/bridge-rectifier-circuit-electronics-basics/?srsltid=AfmBOoryVxeY2vJPQQx7pVCydWM863H0Z2BnXjfGgAjPQ4998pYoG4KH&utm_source=chatgpt.com)
PIV per diode
\[ PIV=V_m \]
Practical bridge output
Two diodes conduct in series during each half-cycle:
\[ V_{out,peak}\approx V_m-2V_F \]
Where \(V_F\) is the forward voltage drop of one diode.
Rectifier comparison table
Parameter
Half-wave
Centre-tapped full-wave
Bridge
Diodes
1
2
4
Uses both half-cycles
No
Yes
Yes
Ideal \(V_{DC}\)
\(V_m/\pi\)
\(2V_m/\pi\)
\(2V_m/\pi\)
Ripple factor
1.21
0.482
0.482
Maximum efficiency
40.6%
81.2%
81.2%
Ripple frequency
\(f\)
\(2f\)
\(2f\)
PIV per diode
\(V_m\)
\(2V_m\)
\(V_m\)
Centre tap required
No
Yes
No
Note: The table assumes ideal diodes and standard textbook definitions. The exact transformer utilization factor and voltage drops depend on the circuit arrangement.

### 1.4.6 Filters

Definition [DIRECTLY IN NOTES]:
A filter is a circuit connected to the rectifier output to reduce ripple and make the DC output smoother.
The repository's practical experiment specifically includes a capacitor filter connected in parallel with the load.
Capacitor filter working
The capacitor charges near the peak of the rectified waveform.
When the rectified voltage decreases, the diode stops conducting.
The capacitor discharges through the load.
The capacitor supplies the load between peaks.
Output voltage becomes smoother and ripple decreases.
[onclick786: Rectifier,Half wave rectifiers,Half Wave Rectifier with Capacitor Filter,Full Wave Rectifier,Graetz bridge rectifier: a full-wave rectifier using four diodes,Full-wave rectifier using a center tap transformer and 2 diodes,full Wave Rectifier with Capacitor Filter,Diode bridge,Bridge Rectifier,full wave bridge rectifier circuit,full wave bridge rectifier circuit with capacitor filter - onclick786](https://images.openai.com/static-rsc-4/KMKhGYRki17EZTuNnOeOVeWBE78jy2cw5vcsKqc_FmS5MaqyZL7YrNU8X12ilY8wchIYydg0uucKVA39j77z2FrudH95NGOCdm7-NfwHzmH0Ytxcd0q1Sv_9lRivlrsS0ZAAfuVO8Zm3k4tl3dJqtNm4gVIAwmpXNFsHBS9K37U?purpose=inline)
[onclick786.blogspot.com](https://onclick786.blogspot.com/2016/08/half-wave-rectifiers-in-half-wave.html?utm_source=chatgpt.com)
[RESTORED STANDARD EQUATIONS] Capacitor filter
For a half-wave rectifier with a capacitor filter:
\[ V_{r(pp)}\approx\frac{I_L}{fC} \]
\[ r\approx\frac{1}{2\sqrt{3}fR_LC} \]
For a full-wave rectifier:
\[ V_{r(pp)}\approx\frac{I_L}{2fC} \]
\[ r\approx\frac{1}{4\sqrt{3}fR_LC} \]
Where:
\(V_{r(pp)}\) = peak-to-peak ripple voltage, V
\(I_L\) = load current, A
\(f\) = AC supply frequency, Hz
\(C\) = filter capacitance, F
\(R_L\) = load resistance, \(\Omega\)
\(r\) = ripple factor, dimensionless
These are approximate equations for small ripple and a sufficiently large filter capacitor.
Filter precautions
Correct capacitor polarity must be maintained.
Capacitor voltage rating must exceed the maximum expected voltage.
Discharge the capacitor safely before handling.
Larger capacitance generally reduces ripple but increases charging-current peaks.

### 1.4.7 Rectifier advantages, disadvantages and applications

Advantages
AC-to-DC conversion.
Used in DC power supplies.
Used in battery chargers.
Used in industrial power conversion.
Used in electronic equipment.
Disadvantages
Produces ripple.
May require filtering.
Diode losses reduce efficiency.
Can introduce harmonics and electrical noise.
Practical circuits require correct voltage and current ratings.
Applications
Mobile chargers
Power supplies
Radio circuits
Voltage multipliers
Battery charging
UPS and electronic equipment
Unit 1 formula sheet
Formula
Meaning
SI unit
\(np=n_i^2\)
Mass-action law
m\(^{-6}\)
\(E_g=E_C-E_V\)
Energy gap
J or eV
\(V_T=k_BT/q\)
Thermal voltage
V
\(I=I_S(e^{V_D/\eta V_T}-1)\)
Diode equation
A
\(V_{DC}=V_m/\pi\)
Half-wave average
V
\(V_{RMS}=V_m/2\)
Half-wave RMS
V
\(V_{DC}=2V_m/\pi\)
Full-wave average
V
\(V_{RMS}=V_m/\sqrt2\)
Full-wave RMS
V
\(r=\sqrt{(V_{RMS}/V_{DC})^2-1}\)
Ripple factor
Dimensionless
\(\eta=P_{DC}/P_{AC}\times100\)
Efficiency
%
\(PIV=V_m\)
Bridge diode PIV
V
\(PIV=2V_m\)
Centre-tapped PIV
V
\(V_{r(pp)}\approx I_L/(fC)\)
Half-wave capacitor ripple
V
Unit 1: Solved numerical patterns

### Numerical 1: Half-wave rectifier

Question: A half-wave rectifier operates with a 200 V RMS, 50 Hz AC input. Find the DC output voltage, RMS output voltage and PIV. Assume an ideal diode and that 200 V RMS is the rectifier secondary voltage.
Step 1: Given
\[ V_{RMS(in)}=200\text{ V} \]
\[ f=50\text{ Hz} \]
Step 2: Find peak voltage
\[ V_m=\sqrt2 V_{RMS} \]
\[ V_m=1.414\times200 \]
\[ \boxed{V_m=282.8\text{ V}} \]
Step 3: DC output voltage
\[ V_{DC}=\frac{V_m}{\pi} \]
\[ V_{DC}=\frac{282.8}{3.1416} \]
\[ \boxed{V_{DC}=90.0\text{ V}} \]
Step 4: RMS output voltage
\[ V_{RMS(out)}=\frac{V_m}{2} \]
\[ V_{RMS(out)}=\frac{282.8}{2} \]
\[ \boxed{V_{RMS(out)}=141.4\text{ V}} \]
Step 5: PIV
\[ PIV=V_m \]
\[ \boxed{PIV=282.8\text{ V}} \]

### Numerical 2: Full-wave rectifier

Assume a full-wave rectifier has a peak voltage of 100 V.
\[ V_{DC}=\frac{2V_m}{\pi} \]
\[ =\frac{2(100)}{3.1416} \]
\[ \boxed{V_{DC}=63.66\text{ V}} \]
RMS output:
\[ V_{RMS}=\frac{100}{\sqrt2} \]
\[ \boxed{V_{RMS}=70.71\text{ V}} \]
Ripple factor:
\[ r=0.482 \]

### Numerical 3: Zener regulator

Given:
\[ V_{in}=12\text{ V},\quad V_Z=5.1\text{ V} \]
\[ R_S=330\ \Omega,\quad R_L=1\,k\Omega \]
Series current:
\[ I_S=\frac{12-5.1}{330} \]
\[ I_S=0.02091\text{ A}=20.91\text{ mA} \]
Load current:
\[ I_L=\frac{5.1}{1000} \]
\[ I_L=5.1\text{ mA} \]
Zener current:
\[ I_Z=20.91-5.1 \]
\[ \boxed{I_Z=15.81\text{ mA}} \]
Zener power:
\[ P_Z=5.1\times0.01581 \]
\[ \boxed{P_Z\approx80.6\text{ mW}} \]
The Zener must have a suitable power rating and its current must remain within the permitted range.

### Numerical 4: Half-wave capacitor filter

Given:
\[ I_L=20\text{ mA}=0.02\text{ A} \]
\[ f=50\text{ Hz},\quad C=1000\ \mu F=0.001\text{ F} \]
\[ V_{r(pp)}\approx\frac{I_L}{fC} \]
\[ =\frac{0.02}{50\times0.001} \]
\[ \boxed{V_{r(pp)}\approx0.4\text{ V}} \]
Unit 1: Top 5 exam questions
Explain intrinsic and extrinsic semiconductors with energy-band diagrams. Differentiate N-type and P-type materials.
Explain formation of a P-N junction and describe forward and reverse biasing with V-I characteristics.
Explain Zener and avalanche breakdown. Describe a Zener diode as a voltage regulator.
Derive the expressions for DC value, RMS value, ripple factor and efficiency of a half-wave rectifier.
Explain centre-tapped and bridge full-wave rectifiers. Compare their operation, PIV, efficiency and ripple factor.
Important derivation: Half-wave rectifier
For an ideal half-wave rectifier:
\[ i=I_m\sin\theta,\quad 0\leq\theta\leq\pi \]
and
\[ i=0,\quad \pi\leq\theta\leq2\pi \]
Average current over one full cycle:
\[ I_{DC}=\frac{1}{2\pi}\int_0^\pi I_m\sin\theta\,d\theta \]
\[ I_{DC}=\frac{I_m}{2\pi}[-\cos\theta]_0^\pi \]
\[ I_{DC}=\frac{I_m}{2\pi}[1+1] \]
\[ \boxed{I_{DC}=\frac{I_m}{\pi}} \]
RMS current:
\[ I_{RMS}= \sqrt{\frac{1}{2\pi}\int_0^\pi I_m^2\sin^2\theta\,d\theta} \]
Using:
\[ \int_0^\pi\sin^2\theta\,d\theta=\frac{\pi}{2} \]
\[ I_{RMS}= \sqrt{\frac{I_m^2}{2\pi}\times\frac{\pi}{2}} \]
\[ \boxed{I_{RMS}=\frac{I_m}{2}} \]
Ripple factor:
\[ r=\sqrt{\left(\frac{I_{RMS}}{I_{DC}}\right)^2-1} \]
\[ r=\sqrt{\left(\frac{I_m/2}{I_m/\pi}\right)^2-1} \]
\[ r=\sqrt{\frac{\pi^2}{4}-1} \]
\[ \boxed{r=1.21} \]
Efficiency:
\[ \eta=\frac{I_{DC}^2R_L}{I_{RMS}^2R_L} \]
\[ \eta=\left(\frac{I_{DC}}{I_{RMS}}\right)^2 \]
\[ \eta=\left(\frac{2}{\pi}\right)^2 \]
\[ \boxed{\eta=40.6\%} \]

# UNIT 2: BJT TRANSISTORS, BATTERIES AND POWER SUPPLIES


## Chapter 2.1: Bipolar Junction Transistor (BJT)


### 2.1.1 Definition

[DIRECTLY IN NOTES]
A Bipolar Junction Transistor is a three-layer, three-terminal semiconductor device used for amplification and switching.
It contains two P-N junctions.
Types:
NPN transistor
PNP transistor
Terminals:
Emitter
Base
Collector
Construction
Emitter
Heavily doped.
Supplies majority carriers.
Base
Very thin.
Lightly doped.
Controls carrier flow.
Collector
Moderately doped.
Physically designed to collect carriers.
Usually larger in area to dissipate heat.

### 2.1.2 NPN transistor

Construction: A thin P-type base is sandwiched between two N-type regions.
Working in active mode
Emitter-base junction is forward biased.
Collector-base junction is reverse biased.
Electrons move from emitter into base.
A small fraction recombines in the base.
Most electrons cross the base and are collected by the collector.
A small base current controls a much larger collector current.

### 2.1.3 PNP transistor

Construction: A thin N-type base is sandwiched between two P-type regions.
Working in active mode
Emitter-base junction is forward biased.
Collector-base junction is reverse biased.
Holes are injected from emitter into base.
A small fraction recombines.
Most holes reach the collector.
Conventional current directions are opposite to those of the NPN transistor under corresponding bias conditions.
[Bipolar Junction Transistor (BJT) Basics | CircuitBread](https://images.openai.com/static-rsc-4/2Zf0lzXdJqzNwzYc1RfgvnBAQGQ4D5ahIotG1M4ALbxvK9mKyslJ3zANZY4C4bxg8Ps79dZLvXDeZmHoQ5Qjdx4ny8ZfWznEvYG9Aeq0dc6sjRkysBn3NtGIQdObpWidBQKiUBk2JnGU2c1YNHiVrUcjWxwX1n6Utj0gIZCbLQ0?purpose=inline)
[circuitbread.com](https://www.circuitbread.com/study-guides/basic-electronics/bipolar-junction-transistor-bjt-basics?utm_source=chatgpt.com)
⚠ Examiner’s flag: The repository's simplified description of collector as the positive terminal and emitter as the negative terminal is not universally correct. The actual voltage polarity depends on whether the transistor is NPN or PNP and on the operating mode.

### 2.1.4 Transistor current components

The basic current relationship is:
\[ I_E=I_C+I_B \]
Where:
\(I_E\) = emitter current, A
\(I_C\) = collector current, A
\(I_B\) = base current, A
This follows from charge conservation at the transistor terminals.

### 2.1.5 Current amplification factors

Common-base current gain
\[ \alpha=\frac{I_C}{I_E} \]
Common-emitter current gain
\[ \beta=\frac{I_C}{I_B} \]
Common-collector current gain
\[ \gamma=\frac{I_E}{I_B} \]
[RESTORED STANDARD EQUATIONS] Relations between \(\alpha,\beta,\gamma\)
Starting from:
\[ I_E=I_C+I_B \]
Since:
\[ \alpha=\frac{I_C}{I_E} \]
Then:
\[ I_B=I_E-I_C \]
\[ I_B=I_E(1-\alpha) \]
Therefore:
\[ \beta=\frac{I_C}{I_B} \]
\[ \boxed{\beta=\frac{\alpha}{1-\alpha}} \]
Rearranging:
\[ \boxed{\alpha=\frac{\beta}{1+\beta}} \]
For common collector:
\[ \gamma=\frac{I_E}{I_B} \]
Since:
\[ I_E=I_C+I_B \]
\[ \gamma=\frac{I_C}{I_B}+1 \]
\[ \boxed{\gamma=\beta+1} \]
These current gains are dimensionless.

### 2.1.6 Injection efficiency and base transport factor

These terms are explicitly mentioned in the CU course introduction.
Injection efficiency \(\gamma_E\):
The fraction of emitter current contributed by carriers injected from the emitter into the base.
\[ \gamma_E= \frac{\text{Desired carrier injection current}} {\text{Total emitter current}} \]
Base transport factor \(\alpha_T\):
The fraction of carriers injected into the base that reach the collector without recombining in the base.
\[ \alpha_T= \frac{\text{Carriers reaching collector}} {\text{Carriers injected into base}} \]
[RESTORED STANDARD EQUATION]
For a simplified transistor model:
\[ \alpha=\gamma_E\alpha_T \]
Where:
\(\alpha\) = common-base current gain
\(\gamma_E\) = emitter injection efficiency
\(\alpha_T\) = base transport factor
Both factors are dimensionless.

### 2.1.7 Transistor configurations

A transistor can be connected in three basic configurations:
Common Base (CB)
Common Emitter (CE)
Common Collector (CC)
A. Common Base configuration
Definition [DIRECTLY IN NOTES]:
The base terminal is common to the input and output circuits.
Input: Emitter-base
Output: Collector-base
Current gain: \(\alpha\)
Low input resistance
High output resistance
Input characteristic
The curve between emitter current \(I_E\) and emitter-base voltage \(V_{EB}\) at constant collector-base voltage \(V_{CB}\).
Output characteristic
The curve between collector current \(I_C\) and collector-base voltage \(V_{CB}\) at constant emitter current \(I_E\).
B. Common Emitter configuration
Definition [DIRECTLY IN NOTES]:
The emitter terminal is common to the input and output circuits.
Input: Base-emitter
Output: Collector-emitter
Current gain: \(\beta\)
Moderate input resistance
High voltage and power gain
Output is inverted relative to input in a common-emitter voltage amplifier.
Input characteristic
Graph between base current \(I_B\) and base-emitter voltage \(V_{BE}\) at constant \(V_{CE}\).
Output characteristic
Graph between collector current \(I_C\) and collector-emitter voltage \(V_{CE}\) at constant \(I_B\).
C. Common Collector configuration
Definition [DIRECTLY IN NOTES]:
The collector terminal is common to the input and output circuits.
Input: Base-collector
Output: Emitter-collector
Current gain: \(\gamma\)
High input resistance
Low output resistance
Often used as an emitter follower and for impedance matching.
Input characteristic
A graph of base current \(I_B\) against the appropriate input voltage at a specified output condition.
Output characteristic
A graph of emitter current \(I_E\) against output voltage at constant base current.
Configuration comparison
Parameter
CB
CE
CC
Common terminal
Base
Emitter
Collector
Input
Emitter-base
Base-emitter
Base-collector
Output
Collector-base
Collector-emitter
Emitter-collector
Current gain
\(\alpha\)
\(\beta\)
\(\gamma\)
Input resistance
Low
Moderate
High
Output resistance
High
High
Low
Main use
High-frequency applications
Voltage amplification
Buffer / impedance matching
⚠ Examiner’s flag: Some repository slides describe CE input resistance as low. The more accurate comparison is that CE generally has moderate input resistance, higher than CB and lower than CC, depending on the transistor and circuit.

### 2.1.8 Operating regions of BJT

Cut-off region
Transistor is OFF.
Both junctions are reverse biased in the ideal switching description.
Base current is approximately zero.
Collector current is approximately zero.
Active region
Emitter-base junction forward biased.
Collector-base junction reverse biased.
Used for amplification.
Saturation region
Both junctions forward biased.
Transistor is fully ON as a switch.
Collector-emitter voltage is small but not exactly zero in a practical transistor.
Reverse-active region
Emitter-base junction reverse biased.
Collector-base junction forward biased.
Rarely used in normal circuit design.

### 2.1.9 Transistor as a switch

[DIRECTLY IN NOTES]
A transistor operates as an electronic switch by moving between cut-off and saturation.
OFF state: Cut-off
\[ I_B\approx0 \]
\[ I_C\approx0 \]
\[ V_{CE}\approx V_{CC} \]
The transistor acts like an open switch.
ON state: Saturation
\[ I_C\approx I_{C(sat)} \]
\[ V_{CE}\approx V_{CE(sat)} \]
The transistor acts like a closed switch.
[RESTORED STANDARD EQUATIONS]
For a simple NPN low-side switch:
\[ I_{C(sat)}\approx\frac{V_{CC}-V_{CE(sat)}}{R_L} \]
A conservative forced-beta design can use:
\[ I_B\geq\frac{I_{C(sat)}}{\beta_{\text{forced}}} \]
Where:
\(V_{CC}\) = supply voltage, V
\(R_L\) = load resistance, \(\Omega\)
\(I_C\) = collector current, A
\(I_B\) = base current, A
\(V_{CE(sat)}\) = saturation voltage, V
\(\beta_{\text{forced}}\) = selected design current-gain ratio

### 2.1.10 Transistor as an amplifier

Definition [DIRECTLY IN NOTES]:
A transistor acts as an amplifier when a small input signal causes a larger change in output current or voltage.
For a common-emitter amplifier:
Base-emitter junction is forward biased.
Collector-base junction is reverse biased.
DC bias establishes the operating point.
A small AC signal is superimposed on the bias.
The collector current changes.
The collector load converts the current variation into an output voltage variation.
[RESTORED STANDARD EQUATIONS]
Small-signal current gain:
\[ \beta_{ac}=\frac{\Delta I_C}{\Delta I_B} \]
Approximate voltage gain:
\[ A_V=\frac{\Delta V_{out}}{\Delta V_{in}} \]
Power gain:
\[ A_P=\frac{P_{out}}{P_{in}} \]
Where:
\(A_V\) = voltage gain, dimensionless
\(A_P\) = power gain, dimensionless
\(\Delta I_C\) = change in collector current, A
\(\Delta I_B\) = change in base current, A
The repository gives an illustrative example where a 0.1 V signal change causes a 1 mA emitter-current change. This is an example, not a universal transistor parameter.

## Chapter 2.2: Energy storage devices and batteries


### 2.2.1 Energy storage device

Definition [DIRECTLY IN NOTES]:
An energy storage device stores energy in one form and releases it when required.
The repository includes:
Batteries
Capacitors
Fossil-fuel energy storage
Flywheel storage
Superconducting magnetic energy storage (SMES)
Compressed-air energy storage
Pumped-hydro energy storage

### 2.2.2 Battery

Definition [DIRECTLY IN NOTES]:
A battery is an electrochemical energy storage device that converts chemical energy into electrical energy during discharge.
A battery consists of one or more electrochemical cells.
Basic parts
Anode
Cathode
Electrolyte
Separator
Current collectors
External terminals
The exact electrode naming convention can depend on whether the battery is being charged or discharged. In ordinary discharge operation, the anode is the negative electrode and the cathode is the positive electrode.

### 2.2.3 Primary and secondary batteries

Primary battery
Designed mainly for one-time use.
Generally not rechargeable.
Used where replacement is practical.
Examples: alkaline and primary lithium cells.
Secondary battery
Rechargeable.
Can undergo repeated charge-discharge cycles.
Used in phones, laptops, electric vehicles and energy storage.
Examples: lithium-ion, lead-acid and nickel-metal hydride.
Feature
Primary
Secondary
Rechargeability
Usually no
Yes
Reuse
Limited
Repeated cycles
Initial cost
Often lower
Often higher
Typical applications
Remote controls, disposable devices
Phones, laptops, EVs

### 2.2.4 Battery specifications

Terminal voltage
The voltage measured between the battery terminals.
Unit: volt (V).
Nominal voltage
The approximate standard operating voltage assigned to a battery or cell.
Energy capacity
The amount of charge a battery can deliver under specified conditions.
Usually expressed in ampere-hours (Ah).
State of charge (SOC)
The remaining charge relative to the usable or rated capacity.
\[ SOC=\frac{Q_{\text{remaining}}}{Q_{\text{full}}}\times100\% \]
Depth of discharge (DoD)
The fraction of battery capacity already used.
\[ DoD=100\%-SOC \]
Energy
\[ E=VIt \]
For approximately constant voltage and current:
\[ E=VQ \]
Where:
\(E\) = energy, J or Wh
\(V\) = voltage, V
\(I\) = current, A
\(t\) = time, s or h
\(Q\) = charge, C or Ah
Power density
Power delivered per unit mass or volume.
Energy density
Energy stored per unit mass or volume.
Cycle life
The number of charge-discharge cycles a battery can undergo before reaching a defined end-of-life condition.
Durability
The ability of a battery to withstand physical, environmental and operating stresses.
Lifetime
The period over which the battery remains usable.

### 2.2.5 Battery selection parameters

The repository identifies these important selection factors:
Energy density
Power density or current availability
Durability
Lifetime
Reusability
Cycle durability
Application requirements
Additional standard selection considerations [EXAM SUPPORT]
Nominal voltage
Capacity in Ah
Charging time
Discharge rate
Operating temperature
Safety
Weight and size
Cost
Maintenance requirements

### 2.2.6 Battery numerical example

A 12 V battery has a capacity of 50 Ah. Find its nominal energy capacity in Wh.
\[ E=V\times Q \]
\[ E=12\times50 \]
\[ \boxed{E=600\text{ Wh}} \]
In joules:
\[ 600\times3600=2,160,000\text{ J} \]
\[ \boxed{E=2.16\text{ MJ}} \]
This is nominal energy, not a guarantee of usable energy under every load and temperature.

## Chapter 2.3: Linear power supply and SMPS


### 2.3.1 Linear power supply

Definition [DIRECTLY IN NOTES]:
A linear power supply converts an AC input into a regulated DC output using a transformer, rectifier, filter and voltage-regulator stage.
Block diagram
AC input
Step-down transformer
Rectifier
Filter capacitor
Voltage regulator
Regulated DC output
Working
AC input enters the transformer.
Transformer steps the voltage up or down and provides isolation when designed as an isolated transformer.
Rectifier converts AC into pulsating DC.
Filter capacitor reduces ripple.
Voltage regulator stabilizes output voltage.
Output capacitor provides further smoothing.
Role of pass transistor and Zener diode
The repository describes a regulator consisting of a pass transistor and Zener diode.
Zener diode provides a reference voltage.
Pass transistor controls the load current.
Output voltage is maintained approximately constant.
Efficiency
\[ \eta=\frac{P_{out}}{P_{in}}\times100\% \]
The repository states that linear power-supply efficiency is around 40% to 50% in its described context. This is not a universal efficiency limit; actual efficiency depends on circuit design and operating conditions.
Advantages
Low output noise.
Simple operation.
Good for sensitive analogue circuits.
Can provide clean regulated output.
Disadvantages
Pass-transistor power loss.
Heat generation.
Lower efficiency in many designs.
Large transformer and heat sink may be required.

### 2.3.2 Switched-mode power supply (SMPS)

Definition [DIRECTLY IN NOTES]:
An SMPS is an electronic power supply that regulates output by rapidly switching semiconductor devices between ON and OFF states.
Block diagram
AC input
Input rectifier and filter
High-frequency switching stage
High-frequency transformer
Output rectifier and filter
Regulated DC output
Feedback from output to the control unit adjusts switching operation.
Working
AC input is rectified and filtered.
Unregulated DC enters the switching stage.
A power transistor or MOSFET switches rapidly.
High-frequency pulses drive the transformer or conversion stage.
Output is rectified and filtered.
A feedback-control circuit monitors output.
The controller adjusts switching to maintain the required output.
Advantages
High efficiency in many designs.
Smaller and lighter transformer.
Suitable for a wide range of output voltages.
Common in computers, servers, chargers and industrial equipment.
Disadvantages
More complex circuit.
High-frequency switching can produce electromagnetic interference.
Requires appropriate filtering and control.
Troubleshooting can be more difficult.
Linear power supply vs SMPS
Parameter
Linear supply
SMPS
Main control
Linear regulator/pass device
High-frequency switching
Efficiency
Often lower
Often higher
Size
Usually larger
Usually smaller
Heat
Higher in many designs
Often lower
Noise
Generally low
Switching noise possible
Complexity
Relatively simple
More complex
Applications
Analogue, instrumentation
Computers, chargers, servers
Unit 2 formula sheet
Formula
Meaning
SI unit
\(I_E=I_C+I_B\)
BJT current relation
A
\(\alpha=I_C/I_E\)
CB current gain
Dimensionless
\(\beta=I_C/I_B\)
CE current gain
Dimensionless
\(\gamma=I_E/I_B\)
CC current gain
Dimensionless
\(\beta=\alpha/(1-\alpha)\)
Alpha-beta relation
Dimensionless
\(\alpha=\beta/(1+\beta)\)
Beta-alpha relation
Dimensionless
\(\gamma=\beta+1\)
Gamma-beta relation
Dimensionless
\(\alpha=\gamma_E\alpha_T\)
Current transfer factor
Dimensionless
\(I_{C(sat)}\approx(V_{CC}-V_{CE(sat)})/R_L\)
Saturation current
A
\(SOC=Q_r/Q_f\times100\%\)
State of charge
%
\(E=VQ\)
Battery energy
J or Wh
\(P=VI\)
Electrical power
W
\(\eta=P_{out}/P_{in}\times100\%\)
Power-supply efficiency
%
Unit 2: Solved numerical patterns

### Numerical 1: Calculate BJT current gain

Given:
\[ I_C=4\text{ mA},\quad I_B=40\ \mu A \]
Convert:
\[ I_B=40\times10^{-6}\text{ A} \]
\[ \beta=\frac{I_C}{I_B} \]
\[ \beta=\frac{4\times10^{-3}}{40\times10^{-6}} \]
\[ \boxed{\beta=100} \]

### Numerical 2: Find alpha from beta

Given:
\[ \beta=99 \]
\[ \alpha=\frac{\beta}{1+\beta} \]
\[ \alpha=\frac{99}{100} \]
\[ \boxed{\alpha=0.99} \]

### Numerical 3: Find emitter current

Given:
\[ I_C=5\text{ mA},\quad I_B=50\ \mu A \]
\[ I_E=I_C+I_B \]
\[ I_E=5+0.05 \]
\[ \boxed{I_E=5.05\text{ mA}} \]

### Numerical 4: Battery energy

A 24 V battery has a capacity of 20 Ah.
\[ E=V\times Ah \]
\[ E=24\times20 \]
\[ \boxed{E=480\text{ Wh}} \]

### Numerical 5: Linear supply efficiency

A linear power supply receives 100 W and delivers 45 W.
\[ \eta=\frac{45}{100}\times100 \]
\[ \boxed{\eta=45\%} \]
Power loss:
\[ P_{\text{loss}}=P_{in}-P_{out} \]
\[ P_{\text{loss}}=100-45 \]
\[ \boxed{P_{\text{loss}}=55\text{ W}} \]
Unit 2: Top 5 exam questions
Explain the construction and working of NPN and PNP transistors with diagrams.
Derive the relationships between \(\alpha\), \(\beta\) and \(\gamma\). Explain transistor current components.
Explain CB, CE and CC configurations with input and output characteristics.
Explain a transistor as a switch and as an amplifier, including cut-off, active and saturation regions.
Explain primary and secondary batteries, battery specifications and selection parameters. Compare linear power supplies and SMPS.
Important derivation: Alpha-beta relation
Start with:
\[ I_E=I_C+I_B \]
Divide through by \(I_E\):
\[ 1=\frac{I_C}{I_E}+\frac{I_B}{I_E} \]
Since:
\[ \alpha=\frac{I_C}{I_E} \]
Then:
\[ \frac{I_B}{I_E}=1-\alpha \]
Therefore:
\[ \beta=\frac{I_C}{I_B} \]
Multiply numerator and denominator by \(1/I_E\):
\[ \beta=\frac{I_C/I_E}{I_B/I_E} \]
\[ \boxed{\beta=\frac{\alpha}{1-\alpha}} \]
Rearranging:
\[ \boxed{\alpha=\frac{\beta}{1+\beta}} \]

# UNIT 3: ELECTRICAL CIRCUITS, AC CIRCUITS AND TRANSFORMERS


## Chapter 3.1: Basic electrical concepts and circuit elements


### 3.1.1 Electric current

Definition [DIRECTLY IN NOTES]:
Electric current is the rate of flow of electric charge through a conductor.
\[ I=\frac{Q}{t} \]
Where:
\(I\) = current, A
\(Q\) = charge, C
\(t\) = time, s
One ampere means one coulomb of charge passing a point per second.
\[ 1\text{ A}=1\text{ C/s} \]
Conventional current: Defined from positive to negative potential through the external circuit.
Electron flow: In a metallic conductor, electrons drift in the opposite direction to conventional current.

### 3.1.2 Voltage or potential difference

Definition [DIRECTLY IN NOTES]:
Voltage is the work done per unit charge to move a charge between two points.
\[ V=\frac{W}{Q} \]
Where:
\(V\) = voltage, V
\(W\) = work or energy, J
\(Q\) = charge, C
\[ 1\text{ V}=1\text{ J/C} \]

### 3.1.3 Circuit elements

Active elements
Elements capable of supplying energy or providing power gain in a circuit.
Examples: independent sources and controlled sources.
Passive elements
Elements that absorb, store or dissipate energy.
Examples: resistor, capacitor and inductor.
Linear elements
Elements whose voltage-current relationship is linear and which obey superposition under the relevant conditions.
Non-linear elements
Elements whose voltage-current relationship is not linear.
Unilateral elements
Elements whose behaviour depends on the direction of current or voltage.
Example: a diode.
Bilateral elements
Elements whose ideal characteristics remain the same when the direction of current is reversed.
Examples: ideal resistors, inductors and capacitors.
Lumped elements
Elements whose electrical behaviour is represented by concentrated circuit parameters such as \(R\), \(L\) and \(C\).
Distributed elements
Elements whose resistance, inductance and capacitance are distributed along their physical length, such as a transmission line.

### 3.1.4 Resistor, capacitor and inductor

Resistor
Opposes current flow and dissipates electrical energy as heat.
\[ V=IR \]
\(V\): voltage, V
\(I\): current, A
\(R\): resistance, \(\Omega\)
Power:
\[ P=VI=I^2R=\frac{V^2}{R} \]
Capacitor
Stores energy in an electric field.
\[ Q=CV \]
\[ i=C\frac{dv}{dt} \]
Energy:
\[ W_C=\frac12CV^2 \]
\(C\): capacitance, F
\(Q\): charge, C
\(V\): voltage, V
\(i\): current, A
Inductor
Stores energy in a magnetic field.
\[ v=L\frac{di}{dt} \]
Energy:
\[ W_L=\frac12LI^2 \]
\(L\): inductance, H
\(i\): current, A
\(v\): voltage, V

## Chapter 3.2: Kirchhoff's laws


### 3.2.1 Kirchhoff's Current Law (KCL)

Definition [DIRECTLY IN NOTES]:
The algebraic sum of currents at a node is zero. Total current entering a junction equals total current leaving it.
\[ \boxed{\sum I=0} \]
Or:
\[ \sum I_{\text{entering}}=\sum I_{\text{leaving}} \]
Principle: Conservation of electric charge.
[Physics の キルヒホッフの法則 | JoVE Core](https://images.openai.com/static-rsc-4/e3OFporqNwNjTd5U5IGcO43PfQsy7b5t1MBM_MgU1eQIu7QHYfuYyC6uD31EJeLImL5FIoG_tmAbldW3vJYwXZwIeacHFyhVCDg3mgZYqG1YKjI6tQG_LpYukJGbgz33OFUf5N8d_m4Ki01wXtLw9HSgZfmRHnNe9ZW5xTvhmHM?purpose=inline)
[jove.com](https://www.jove.com/ja/science-education/v/13756/kirchhoff-s-rules?utm_source=chatgpt.com)
Example
A node has 5 A and 3 A entering, and current \(I\) leaving.
\[ I=5+3 \]
\[ \boxed{I=8\text{ A}} \]

### 3.2.2 Kirchhoff's Voltage Law (KVL)

Definition [DIRECTLY IN NOTES]:
The algebraic sum of all voltages around a closed loop is zero.
\[ \boxed{\sum V=0} \]
Principle: Conservation of energy.
For the repository's illustrated series-loop form:
\[ V_1-IR_1-V_2-IR_2-IR_3=0 \]
Rearranging:
\[ V_1-V_2=I(R_1+R_2+R_3) \]
[Kirchhoff's Voltage Law (KVL) Explained](https://images.openai.com/static-rsc-4/ZB68fjEjZflxwxqS9Drmvrh6SXb84F4Ld8I-0uQFp13GxRGPo9E9JBzYy06kAscIdR6d2CN1jTAoQv5efnWXiS7bCdB9O8jdtL3R5-ahVYR3PZOjdiN5fyvFf8ulUNAz-HUcUWh8G0CN9ZMCyOF-DOc1dij57e4nFqcD_yQVjcc?purpose=inline)
[rumble.com](https://rumble.com/v39al13-kirchhoffs-voltage-law-kvl-explained.html?utm_source=chatgpt.com)
Example
A 12 V source supplies two series resistors of 2 \(\Omega\) and 4 \(\Omega\).
Using KVL:
\[ 12-2I-4I=0 \]
\[ 12=6I \]
\[ \boxed{I=2\text{ A}} \]
Voltage drops:
\[ V_1=IR_1=2\times2=4\text{ V} \]
\[ V_2=IR_2=2\times4=8\text{ V} \]
Check:
\[ 12-4-8=0 \]

## Chapter 3.3: AC circuits and waveforms


### 3.3.1 Alternating current

Definition [DIRECTLY IN NOTES]:
Alternating current is an electric current whose magnitude and direction change periodically with time.
A sinusoidal voltage can be expressed as:
\[ v=V_m\sin\omega t \]
A sinusoidal current:
\[ i=I_m\sin(\omega t+\phi) \]
Where:
\(V_m\) = peak voltage, V
\(I_m\) = peak current, A
\(\omega\) = angular frequency, rad s\(^{-1}\)
\(t\) = time, s
\(\phi\) = phase angle, rad or degrees

### 3.3.2 Period and frequency

Period: Time taken to complete one full cycle.
\[ T=\frac1f \]
Frequency: Number of cycles completed per second.
\[ f=\frac1T \]
Where:
\(T\) = period, s
\(f\) = frequency, Hz
Angular frequency:
\[ \omega=2\pi f \]
Unit: rad s\(^{-1}\).

### 3.3.3 Peak, peak-to-peak and average values

Peak value: Maximum magnitude of the waveform.
Peak-to-peak value:
\[ V_{pp}=2V_m \]
For a symmetric sinusoidal waveform.
Average value of a full-cycle sine wave
\[ V_{avg}=0 \]
Average value of a rectified sine wave
\[ V_{avg}=\frac{2V_m}{\pi} \]
For a half-wave rectified sine wave:
\[ V_{avg}=\frac{V_m}{\pi} \]
⚠ Examiner’s flag: The repository gives 0.637 times the peak value as the average value. That is correct for a full-wave rectified sine wave, not for the algebraic average over a complete unrectified sine-wave cycle.

### 3.3.4 RMS value

Definition [DIRECTLY IN NOTES]:
RMS is the effective AC value that produces the same heating effect in a resistor as an equivalent DC value.
For a sinusoidal waveform:
\[ V_{RMS}=\frac{V_m}{\sqrt2} \]
\[ I_{RMS}=\frac{I_m}{\sqrt2} \]
Therefore:
\[ V_{RMS}=0.707V_m \]
\[ I_{RMS}=0.707I_m \]

### 3.3.5 Average value

For a full-wave rectified sine wave:
\[ V_{avg}=\frac{2V_m}{\pi} \]
\[ V_{avg}=0.637V_m \]
For a half-wave rectified sine wave:
\[ V_{avg}=\frac{V_m}{\pi} \]
\[ V_{avg}=0.318V_m \]

### 3.3.6 Peak factor or crest factor

Definition [DIRECTLY IN NOTES]:
The ratio of maximum value to RMS value.
\[ \text{Peak factor}=\frac{V_m}{V_{RMS}} \]
For a sine wave:
\[ \boxed{\text{Peak factor}=\sqrt2=1.414} \]
The same ratio applies to current.

### 3.3.7 Form factor

Definition [DIRECTLY IN NOTES]:
The ratio of RMS value to average rectified value.
\[ \text{Form factor}=\frac{V_{RMS}}{V_{avg}} \]
For a sine wave:
\[ \text{Form factor}= \frac{V_m/\sqrt2}{2V_m/\pi} \]
\[ \boxed{\text{Form factor}=1.11} \]

## Chapter 3.4: Series RL circuit

Definition
[DIRECTLY IN NOTES]
A series RL circuit consists of a resistor and an inductor connected in series to an AC source.
[Visualizing Phasor Diagrams in RLC Circuits: Simplifying Complex Electrical Systems](https://images.openai.com/static-rsc-4/FyGHRwmmbjOCcL8OLG5BVrA1imqdNaMdKbyXHGp052NvlJNSnSNlFN3MBmH3zLB_FocGUBvtOEcXbdf_dt4gylx9x3341VXdUvTdg8U3RzAvKEGIyIHmTm-q8nMtwn2dVG-I3nkqCOi59au-SNNmbEkSwTgZ8XSfjPUC1UEnlpY?purpose=inline)
[wirecrafted.com](https://wirecrafted.com/phasor-diagram-rlc-circuit.html?utm_source=chatgpt.com)
Working principle
AC voltage is applied to the series circuit.
Current flows through both components.
The resistor voltage is in phase with current.
Inductor voltage leads current by \(90^\circ\).
The supply voltage is the phasor sum of the resistor and inductor voltages.
Current lags the supply voltage.
Inductive reactance
\[ X_L=2\pi fL \]
Where:
\(X_L\) = inductive reactance, \(\Omega\)
\(f\) = frequency, Hz
\(L\) = inductance, H
Impedance
\[ Z=\sqrt{R^2+X_L^2} \]
Where:
\(Z\) = impedance, \(\Omega\)
\(R\) = resistance, \(\Omega\)
Current
\[ I=\frac{V}{Z} \]
Phase angle
\[ \tan\phi=\frac{X_L}{R} \]
\[ \phi=\tan^{-1}\left(\frac{X_L}{R}\right) \]
Power factor
\[ \cos\phi=\frac{R}{Z} \]
For an RL circuit, the power factor is lagging.
Voltage drops
\[ V_R=IR \]
\[ V_L=IX_L \]
\[ V=\sqrt{V_R^2+V_L^2} \]
Power
Real power:
\[ P=VI\cos\phi \]
Also:
\[ P=I^2R \]
Reactive power:
\[ Q=VI\sin\phi \]
Apparent power:
\[ S=VI \]
Units:
\(P\): watt (W)
\(Q\): volt-ampere reactive (var)
\(S\): volt-ampere (VA)

## Chapter 3.5: Series RC circuit

Definition
[DIRECTLY IN NOTES]
A series RC circuit consists of a resistor and capacitor connected in series to an AC source.
[RC 시리즈 회로의 상세한 분석](https://images.openai.com/static-rsc-4/Z6Ga4948JEkwoMeztxn25tm_FUxlzuEsiDWMhaFoXX-4lFb8VvTxFyVWibypCfa18ifALBvGQelcKp-d91VL-7o-XSFgPW4mkifieNhuijcgPTEOUl7oDEJnXto1KRj2IZcardIzQhf-aAleqO73DSLZxWNkQEzSo6-J3ESjlsU?purpose=inline)
[ariat-tech.kr](https://www.ariat-tech.kr/blog/detailed-analysis-of-rc-series-circuit.html?utm_source=chatgpt.com)
Working principle
AC voltage is applied.
Current flows through the resistor and capacitor.
Resistor voltage is in phase with current.
Capacitor voltage lags current by \(90^\circ\).
Supply voltage is the phasor sum of the two voltage drops.
Current leads the supply voltage.
Capacitive reactance
\[ X_C=\frac{1}{2\pi fC} \]
Where:
\(X_C\) = capacitive reactance, \(\Omega\)
\(f\) = frequency, Hz
\(C\) = capacitance, F
Impedance
\[ Z=\sqrt{R^2+X_C^2} \]
Current
\[ I=\frac{V}{Z} \]
Phase angle
\[ \tan\phi=\frac{X_C}{R} \]
The magnitude of phase angle is:
\[ \phi=\tan^{-1}\left(\frac{X_C}{R}\right) \]
Current leads the supply voltage.
Power factor
\[ \cos\phi=\frac{R}{Z} \]
For an RC circuit, the power factor is leading.
Voltage drops
\[ V_R=IR \]
\[ V_C=IX_C \]
\[ V=\sqrt{V_R^2+V_C^2} \]

## Chapter 3.6: Series RLC circuit

The repository's lecture slides include RLC numerical references and a series RLC recap, even though the detailed extracted lecture explanation focuses more heavily on RL and RC. The following is the standard series RLC treatment for that slide-listed material.
Definition [EXAM SUPPORT]:
A series RLC circuit consists of a resistor, inductor and capacitor connected in series to an AC supply.
[AC circuit containing a resistor, an inductor and a capacitor in series - Series RLC circuit - Phasor diagram, Circuit Diagram, Formula, Solved Example Problems | Alternating Current (AC)](https://images.openai.com/static-rsc-4/CVpYznvxQMNT32eFjkOM9tpfn9egcLk4rEj7FMkjTeKlfd2M1ZfdsZ3DIuSRlh9oV9EfTIZIdQm6R3oUbZAyxkKw6juGWqVIQfVDo_mNVNTmO19Wwo2kuQ8PtPjzEZ1d0tX0gWCp91OJkOtJWJl66zuEkuR13On_llGdYsclAAo?purpose=inline)
[brainkart.com](https://www.brainkart.com/article/AC-circuit-containing-a-resistor%2C-an-inductor-and-a-capacitor-in-series---Series-RLC-circuit_38523/?utm_source=chatgpt.com)
Reactances
\[ X_L=2\pi fL \]
\[ X_C=\frac{1}{2\pi fC} \]
Net reactance
\[ X=X_L-X_C \]
Impedance
\[ Z=\sqrt{R^2+(X_L-X_C)^2} \]
Current
\[ I=\frac{V}{Z} \]
Phase angle
\[ \tan\phi=\frac{X_L-X_C}{R} \]
Power factor
\[ \cos\phi=\frac{R}{Z} \]
Circuit behaviour
If \(X_L>X_C\): circuit is inductive and current lags.
If \(X_C>X_L\): circuit is capacitive and current leads.
If \(X_L=X_C\): circuit is at resonance.
Resonance
At resonance:
\[ X_L=X_C \]
\[ 2\pi f_rL=\frac{1}{2\pi f_rC} \]
Rearranging:
\[ \boxed{f_r=\frac{1}{2\pi\sqrt{LC}}} \]
At series resonance:
\[ Z=R \]
\[ I_{\max}=\frac{V}{R} \]
\[ \cos\phi=1 \]
Quality factor
\[ Q_f=\frac{\omega_r L}{R} \]
or
\[ Q_f=\frac{1}{\omega_r CR} \]
This is dimensionless.

## Chapter 3.7: Transformers


### 3.7.1 Definition

[DIRECTLY IN NOTES]
A transformer is a static electrical device that transfers AC electrical energy from one circuit to another by electromagnetic induction, usually changing voltage and current while keeping frequency constant.

### 3.7.2 Principle of operation

A transformer works on:
Faraday's law of electromagnetic induction.
Mutual induction.
Lenz's law.
Faraday's law
The magnitude of induced EMF is proportional to the rate of change of magnetic flux linkage.
\[ e=-N\frac{d\phi}{dt} \]
Where:
\(e\) = induced EMF, V
\(N\) = number of turns
\(\phi\) = magnetic flux, Wb
\(t\) = time, s
The negative sign represents Lenz's law.

### 3.7.3 Construction of transformer

Parts [DIRECTLY IN NOTES]
Magnetic core
Primary winding
Secondary winding
Insulation
Tank
Transformer oil, for oil-immersed types
Oil conservator
Breather
Radiators and fans
Core
Provides a path for magnetic flux.
Usually laminated to reduce eddy-current loss.
Made of appropriate magnetic material.
Windings
Primary winding receives the input supply.
Secondary winding provides the output.
Usually made of insulated copper conductors.
Insulation
Prevents unwanted electrical contact between windings and core.
Tank
Protects internal components and, in oil-filled transformers, contains the insulating oil.
Transformer oil
Provides insulation and helps dissipate heat.
Conservator
Provides space for oil expansion and contraction in suitable oil-immersed transformers.
Breather
Helps prevent moisture entering the oil system.
Radiators and fans
Help remove heat.

### 3.7.4 Types of transformers

Step-up transformer
Secondary voltage greater than primary voltage.
Secondary turns greater than primary turns.
\[ N_2>N_1 \]
Step-down transformer
Secondary voltage less than primary voltage.
Secondary turns less than primary turns.
\[ N_2<N_1 \]
Based on core material
Iron-core transformer
Ferrite-core transformer
Based on winding arrangement
Conventional two-winding transformer
Autotransformer

### 3.7.5 Working of transformer

AC voltage is applied to the primary winding.
Alternating current creates alternating magnetic flux in the core.
Flux links the secondary winding.
An EMF is induced in the secondary winding.
When a load is connected, secondary current flows.
Power is transferred magnetically between the windings.
Important: A conventional transformer requires changing magnetic flux. It does not operate as a normal transformer on steady DC.

### 3.7.6 EMF equation of transformer

[DIRECTLY IN NOTES as a topic; equation restored from standard textbook derivation]
Let:
\(\phi_m\) = maximum flux, Wb
\(f\) = frequency, Hz
\(N_1\) = primary turns
\(N_2\) = secondary turns
Assume sinusoidal flux:
\[ \phi=\phi_m\sin\omega t \]
By Faraday's law:
\[ e=-N\frac{d\phi}{dt} \]
Differentiate:
\[ \frac{d\phi}{dt}=\omega\phi_m\cos\omega t \]
Therefore:
\[ e=-N\omega\phi_m\cos\omega t \]
Maximum induced EMF:
\[ E_m=N\omega\phi_m \]
Since:
\[ \omega=2\pi f \]
\[ E_m=2\pi fN\phi_m \]
For a sinusoidal waveform:
\[ E_{RMS}=\frac{E_m}{\sqrt2} \]
\[ E_{RMS}=\frac{2\pi fN\phi_m}{\sqrt2} \]
\[ \boxed{E=4.44fN\phi_m} \]
Thus:
Primary induced EMF:
\[ \boxed{E_1=4.44fN_1\phi_m} \]
Secondary induced EMF:
\[ \boxed{E_2=4.44fN_2\phi_m} \]
Where:
\(E_1,E_2\) = RMS induced EMFs, V
\(f\) = frequency, Hz
\(N_1,N_2\) = turns
\(\phi_m\) = maximum flux, Wb

### 3.7.7 Turns ratio and transformation ratio

Turns ratio
The ratio of primary turns to secondary turns:
\[ \text{Turns ratio}=\frac{N_1}{N_2} \]
Transformation ratio
The ratio of secondary voltage to primary voltage:
\[ K=\frac{V_2}{V_1} \]
For an ideal transformer:
\[ \boxed{\frac{V_2}{V_1}=\frac{N_2}{N_1}} \]
Also:
\[ \frac{I_2}{I_1}=\frac{N_1}{N_2} \]
For an ideal transformer:
\[ V_1I_1=V_2I_2 \]
⚠ Examiner’s flag: The repository sometimes describes the turns ratio and transformation ratio with inconsistent numerator order. Remember the convention above: \(K=V_2/V_1=N_2/N_1\).

### 3.7.8 Transformer losses

The repository explicitly identifies six types.
1. Iron or core losses
Losses due to alternating magnetic flux in the core.
Two components:
Hysteresis loss
Eddy-current loss
2. Hysteresis loss
Caused by repeated magnetization and demagnetization of the transformer core.
[RESTORED STANDARD EQUATION] Steinmetz form
\[ P_h=K_h f B_m^n V_c \]
Where:
\(P_h\) = hysteresis power loss, W
\(K_h\) = material-dependent coefficient
\(f\) = frequency, Hz
\(B_m\) = maximum flux density, T
\(n\) = Steinmetz exponent
\(V_c\) = core volume, m\(^3\)
The exact coefficient and exponent depend on core material.
3. Eddy-current loss
Alternating flux induces circulating currents in the conducting core. These currents cause heating.
[RESTORED STANDARD EQUATION]
\[ P_e=K_e B_m^2 f^2 t^2 V_c \]
Where:
\(P_e\) = eddy-current loss, W
\(K_e\) = material and unit-dependent coefficient
\(B_m\) = maximum flux density, T
\(f\) = frequency, Hz
\(t\) = lamination thickness, m
\(V_c\) = core volume, m\(^3\)
4. Copper loss
Due to resistance of the primary and secondary windings.
\[ P_{cu}=I_1^2R_1+I_2^2R_2 \]
Where:
\(I_1\) = primary current, A
\(I_2\) = secondary current, A
\(R_1\) = primary resistance, \(\Omega\)
\(R_2\) = secondary resistance, \(\Omega\)
Copper loss varies approximately with the square of load current.
5. Stray loss
Caused by leakage flux inducing currents in structural and other conducting parts.
6. Dielectric loss
Loss in insulating materials such as transformer oil and solid insulation.

### 3.7.9 Transformer efficiency

Definition [DIRECTLY IN NOTES]:
Transformer efficiency is the ratio of output power to input power.
\[ \boxed{\eta=\frac{P_{out}}{P_{in}}\times100\%} \]
Since:
\[ P_{in}=P_{out}+P_{\text{loss}} \]
\[ \boxed{\eta=\frac{P_{out}}{P_{out}+P_{\text{loss}}}\times100\%} \]
Where:
\(\eta\) = efficiency, %
\(P_{out}\) = output power, W
\(P_{in}\) = input power, W
\(P_{\text{loss}}\) = total power loss, W
For a load at power factor \(\cos\phi\):
\[ P_{out}=V_2I_2\cos\phi \]
For a transformer rated in kVA:
\[ P_{out}=\text{kVA}\times1000\times\cos\phi \]

### 3.7.10 Transformer voltage regulation

Definition [DIRECTLY IN NOTES]:
Voltage regulation measures the change in secondary terminal voltage between no-load and full-load conditions, with primary voltage held constant.
\[ \boxed{\%VR=\frac{E_2-V_2}{V_2}\times100\%} \]
Where:
\(E_2\) = no-load secondary voltage, V
\(V_2\) = full-load secondary terminal voltage, V
A smaller positive voltage regulation generally indicates better voltage regulation for the same operating conditions.

### 3.7.11 Transformer applications

[DIRECTLY IN NOTES]
Increasing AC voltage for transmission.
Reducing voltage for electrical equipment.
Electrical isolation between circuits.
Voltage conversion in power systems.
Power supplies.
Industrial and instrumentation systems.
Unit 3 formula sheet
Formula
Meaning
SI unit
\(I=Q/t\)
Current
A
\(V=W/Q\)
Voltage
V
\(V=IR\)
Ohm's law
V
\(P=VI\)
Electrical power
W
\(\sum I=0\)
KCL
A
\(\sum V=0\)
KVL
V
\(T=1/f\)
Period
s
\(\omega=2\pi f\)
Angular frequency
rad s\(^{-1}\)
\(V_{RMS}=V_m/\sqrt2\)
Sinusoidal RMS voltage
V
\(I_{RMS}=I_m/\sqrt2\)
Sinusoidal RMS current
A
\(V_{avg}=2V_m/\pi\)
Full-wave rectified average
V
\(V_{avg}=V_m/\pi\)
Half-wave rectified average
V
\(V_{pp}=2V_m\)
Peak-to-peak voltage
V
\(X_L=2\pi fL\)
Inductive reactance
\(\Omega\)
\(X_C=1/(2\pi fC)\)
Capacitive reactance
\(\Omega\)
\(Z=\sqrt{R^2+X_L^2}\)
RL impedance
\(\Omega\)
\(Z=\sqrt{R^2+X_C^2}\)
RC impedance
\(\Omega\)
\(Z=\sqrt{R^2+(X_L-X_C)^2}\)
RLC impedance
\(\Omega\)
\(\cos\phi=R/Z\)
Power factor
Dimensionless
\(f_r=1/(2\pi\sqrt{LC})\)
Resonant frequency
Hz
\(e=-N(d\phi/dt)\)
Faraday's law
V
\(E=4.44fN\phi_m\)
Transformer EMF equation
V
\(K=V_2/V_1=N_2/N_1\)
Transformation ratio
Dimensionless
\(P_{cu}=I_1^2R_1+I_2^2R_2\)
Copper loss
W
\(\eta=P_{out}/P_{in}\times100\)
Transformer efficiency
%
\(\%VR=(E_2-V_2)/V_2\times100\)
Voltage regulation
%
Unit 3: Solved numerical patterns

### Numerical 1: KCL

At a junction, 6 A and 4 A enter, while 3 A and \(I\) leave.
\[ 6+4=3+I \]
\[ 10=3+I \]
\[ \boxed{I=7\text{ A}} \]

### Numerical 2: KVL

A 24 V source supplies two series resistors of 4 \(\Omega\) and 8 \(\Omega\).
\[ 24-4I-8I=0 \]
\[ 24=12I \]
\[ \boxed{I=2\text{ A}} \]
Voltage drops:
\[ V_1=2\times4=8\text{ V} \]
\[ V_2=2\times8=16\text{ V} \]
Check:
\[ 8+16=24\text{ V} \]

### Numerical 3: AC RMS and peak value

A sinusoidal voltage has peak value 325 V. Find RMS voltage.
\[ V_{RMS}=\frac{V_m}{\sqrt2} \]
\[ V_{RMS}=\frac{325}{1.414} \]
\[ \boxed{V_{RMS}=229.8\text{ V}} \]

### Numerical 4: Series RL circuit

Given:
\[ V=100\text{ V},\quad f=50\text{ Hz} \]
\[ R=20\ \Omega,\quad L=0.1\text{ H} \]
Step 1: Inductive reactance
\[ X_L=2\pi fL \]
\[ X_L=2\pi(50)(0.1) \]
\[ \boxed{X_L=31.42\ \Omega} \]
Step 2: Impedance
\[ Z=\sqrt{R^2+X_L^2} \]
\[ Z=\sqrt{20^2+31.42^2} \]
\[ \boxed{Z=37.25\ \Omega} \]
Step 3: Current
\[ I=\frac{V}{Z} \]
\[ I=\frac{100}{37.25} \]
\[ \boxed{I=2.685\text{ A}} \]
Step 4: Phase angle
\[ \phi=\tan^{-1}\left(\frac{31.42}{20}\right) \]
\[ \boxed{\phi\approx57.5^\circ} \]
The current lags the voltage.
Step 5: Power factor
\[ \cos\phi=\frac{20}{37.25} \]
\[ \boxed{\cos\phi\approx0.537\text{ lagging}} \]

### Numerical 5: Series RC circuit

Given:
\[ V=230\text{ V},\quad f=60\text{ Hz} \]
\[ R=100\ \Omega,\quad C=10\ \mu F \]
Convert capacitance:
\[ C=10\times10^{-6}\text{ F} \]
Step 1: Capacitive reactance
\[ X_C=\frac{1}{2\pi fC} \]
\[ X_C=\frac{1}{2\pi(60)(10\times10^{-6})} \]
\[ \boxed{X_C=265.26\ \Omega} \]
Step 2: Impedance
\[ Z=\sqrt{R^2+X_C^2} \]
\[ Z=\sqrt{100^2+265.26^2} \]
\[ \boxed{Z=283.49\ \Omega} \]
Step 3: Current
\[ I=\frac{230}{283.49} \]
\[ \boxed{I=0.811\text{ A}} \]
Step 4: Power factor
\[ \cos\phi=\frac{R}{Z} \]
\[ \cos\phi=\frac{100}{283.49} \]
\[ \boxed{\cos\phi=0.353\text{ leading}} \]

### Numerical 6: Series RLC circuit

Given:
\[ R=10\ \Omega,\quad L=0.1\text{ H} \]
\[ C=100\ \mu F,\quad f=50\text{ Hz} \]
Inductive reactance:
\[ X_L=2\pi(50)(0.1) \]
\[ X_L=31.42\ \Omega \]
Capacitive reactance:
\[ X_C=\frac{1}{2\pi(50)(100\times10^{-6})} \]
\[ X_C=31.83\ \Omega \]
Net reactance:
\[ X=X_L-X_C \]
\[ X=31.42-31.83=-0.41\ \Omega \]
Impedance:
\[ Z=\sqrt{10^2+(-0.41)^2} \]
\[ \boxed{Z\approx10.01\ \Omega} \]
Power factor:
\[ \cos\phi=\frac{10}{10.01} \]
\[ \boxed{\cos\phi\approx0.999\text{ leading}} \]
The circuit is slightly capacitive.

### Numerical 7: Transformer EMF

Given:
\[ f=50\text{ Hz},\quad N_1=500 \]
\[ \phi_m=0.02\text{ Wb} \]
Primary EMF:
\[ E_1=4.44fN_1\phi_m \]
\[ E_1=4.44(50)(500)(0.02) \]
\[ \boxed{E_1=2220\text{ V}} \]

### Numerical 8: Transformer turns ratio

A transformer has 1000 primary turns and 250 secondary turns. Find its voltage ratio.
\[ \frac{V_2}{V_1}=\frac{N_2}{N_1} \]
\[ \frac{V_2}{V_1}=\frac{250}{1000} \]
\[ \boxed{K=0.25} \]
Since \(N_2<N_1\), it is a step-down transformer.
If the primary voltage is 230 V:
\[ V_2=230(0.25) \]
\[ \boxed{V_2=57.5\text{ V}} \]

### Numerical 9: Transformer efficiency

A transformer delivers 5 kW at an efficiency of 95%. Find total loss.
\[ \eta=\frac{P_{out}}{P_{in}} \]
\[ 0.95=\frac{5000}{P_{in}} \]
\[ P_{in}=\frac{5000}{0.95} \]
\[ P_{in}=5263.16\text{ W} \]
Loss:
\[ P_{\text{loss}}=P_{in}-P_{out} \]
\[ P_{\text{loss}}=5263.16-5000 \]
\[ \boxed{P_{\text{loss}}=263.16\text{ W}} \]

### Numerical 10: Transformer voltage regulation

Given:
\[ E_2=240\text{ V} \]
\[ V_2=230\text{ V} \]
\[ \%VR=\frac{E_2-V_2}{V_2}\times100 \]
\[ =\frac{240-230}{230}\times100 \]
\[ \boxed{\%VR=4.35\%} \]
Unit 3: Top 5 exam questions
State and explain Kirchhoff's Current Law and Voltage Law with suitable circuit examples.
Define RMS value, average value, form factor and peak factor. Derive the RMS value of a sinusoidal waveform.
Explain series RL and RC circuits with circuit diagrams, phasor diagrams, impedance and power-factor equations.
Explain the construction and working principle of a transformer. Derive its EMF equation.
Explain transformer losses, efficiency and voltage regulation with relevant equations.
Important derivation: RMS value of a sine wave
Let:
\[ v=V_m\sin\theta \]
The RMS value is:
\[ V_{RMS}=\sqrt{\frac{1}{2\pi}\int_0^{2\pi}v^2d\theta} \]
Substitute:
\[ V_{RMS}= \sqrt{\frac{1}{2\pi}\int_0^{2\pi}V_m^2\sin^2\theta\,d\theta} \]
Take the constant outside:
\[ V_{RMS}= V_m\sqrt{\frac{1}{2\pi}\int_0^{2\pi}\sin^2\theta\,d\theta} \]
Using:
\[ \int_0^{2\pi}\sin^2\theta\,d\theta=\pi \]
Therefore:
\[ V_{RMS}=V_m\sqrt{\frac{\pi}{2\pi}} \]
\[ \boxed{V_{RMS}=\frac{V_m}{\sqrt2}} \]
Final consolidated revision tables
Essential definitions to memorize
Term
One-line definition
Semiconductor
Material with conductivity between conductor and insulator
Intrinsic semiconductor
Pure semiconductor without intentional doping
Extrinsic semiconductor
Semiconductor whose conductivity is modified by doping
Doping
Controlled addition of impurity atoms
Majority carriers
More numerous charge carriers in a doped semiconductor
Minority carriers
Less numerous charge carriers
Hole
Missing electron that behaves as a positive carrier
Depletion region
Junction region depleted of mobile majority carriers
Forward bias
P-side positive and N-side negative
Reverse bias
P-side negative and N-side positive
Zener diode
Heavily doped diode designed for reverse breakdown operation
Rectifier
Circuit converting AC to pulsating DC
Filter
Circuit reducing rectifier output ripple
Ripple factor
Ratio of RMS ripple to DC component
BJT
Three-terminal semiconductor device used for switching and amplification
Alpha
CB current gain
Beta
CE current gain
Gamma
CC current gain
Cut-off
Transistor OFF region
Saturation
Transistor fully ON switching region
Battery
Electrochemical device storing and delivering energy
SOC
Percentage of remaining battery charge
SMPS
Power supply using high-frequency switching
Current
Rate of flow of electric charge
Voltage
Work done per unit charge
KCL
Sum of currents entering a node equals sum leaving
KVL
Algebraic sum of voltages around a closed loop is zero
RMS
Effective AC value based on equal heating effect
Form factor
RMS value divided by rectified average value
Peak factor
Peak value divided by RMS value
Reactance
Opposition to AC caused by inductance or capacitance
Impedance
Total opposition to AC
Power factor
Ratio of real power to apparent power
Transformer
Static device transferring AC energy by electromagnetic induction
Transformation ratio
Secondary voltage divided by primary voltage
Efficiency
Output power divided by input power
Voltage regulation
Change in secondary voltage between no-load and load conditions
High-priority numerical formulas
Unit 1
\[ V_{DC(HW)}=\frac{V_m}{\pi} \]
\[ V_{DC(FW)}=\frac{2V_m}{\pi} \]
\[ V_{RMS}=\frac{V_m}{\sqrt2} \]
\[ r_{HW}=1.21,\quad r_{FW}=0.482 \]
Unit 2
\[ I_E=I_C+I_B \]
\[ \alpha=\frac{\beta}{1+\beta} \]
\[ \beta=\frac{\alpha}{1-\alpha} \]
\[ \gamma=\beta+1 \]
Unit 3
\[ X_L=2\pi fL \]
\[ X_C=\frac{1}{2\pi fC} \]
\[ Z_{RL}=\sqrt{R^2+X_L^2} \]
\[ Z_{RC}=\sqrt{R^2+X_C^2} \]
\[ Z_{RLC}=\sqrt{R^2+(X_L-X_C)^2} \]
\[ E=4.44fN\phi_m \]
\[ \eta=\frac{P_{out}}{P_{in}}\times100\% \]
\[ \%VR=\frac{E_2-V_2}{V_2}\times100\% \]

# Common Mistakes to Avoid in the Exam

Do not write \(0.637V_m\) as the average of a complete unrectified sine wave. Its average over a full cycle is zero.
Do not confuse half-wave and full-wave rectifier RMS values.
Do not use \(PIV=2V_m\) for a bridge rectifier. The standard bridge PIV per diode is \(V_m\).
Do not confuse \(\alpha\) and \(\beta\). Alpha is CB gain; beta is CE gain.
Do not write that a transistor is an amplifier in cut-off or saturation. Amplification occurs in the active region.
Do not assume every transistor has the same 0.7 V base-emitter voltage. It is an approximate silicon BJT value under normal conditions.
Do not forget to convert microfarads into farads before calculating \(X_C\).
Do not use \(X_L\) in an RC impedance calculation or \(X_C\) in an RL calculation.
Do not confuse inductive and capacitive power factors. RL is lagging; RC is leading.
Do not confuse turns ratio \(N_1/N_2\) with transformation ratio \(V_2/V_1=N_2/N_1\).
Do not omit transformer copper loss from total loss.
Do not confuse no-load secondary voltage with full-load secondary voltage in voltage regulation.

# Final Scope and Source Limitations

This compendium follows the repository's course introduction and lecture topics, rather than expanding into unrelated semiconductor material.
The repository also has limitations worth knowing:
Some mathematical equations are missing from extracted slide text, so the restored equations are explicitly labelled.
Some topics, particularly the RLC circuit treatment, appear more clearly in presentation slides than in the detailed lecture prose.
The repository's theory-syllabus field is blank in the extracted master file. The unit boundaries here therefore follow the detailed course introduction and lecture materials.
The repository contains practical experiments and slide content in addition to theory. The half-wave rectifier with and without a capacitor filter is specifically supported by its practical experiment.
The repository does not establish a verified statistical ranking of past examination questions. The questions above are high-priority predictions based on the lecture topics, slide quizzes and course outcomes, not verified repeated-paper statistics.
My revision recommendation: Prioritize the derivations of half-wave and full-wave rectifiers, alpha-beta-gamma relations, KCL/KVL, RMS value, RL/RC impedance and power factor, and the transformer EMF equation, losses and efficiency. These are the strongest formula-and-derivation areas across the actual three-unit material.
