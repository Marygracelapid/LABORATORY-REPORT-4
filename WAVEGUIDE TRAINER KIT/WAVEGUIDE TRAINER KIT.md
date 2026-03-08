# Experiment 22: Microwave Waveguide Trainer Kit

## I. Objectives

The objectives of this experiment are as follows:

- **Hardware Identification:** To identify and classify the various hardware modules used in a professional **X-band (8.2–12.4 GHz) microwave waveguide bench**.
- **Microwave Transmission Analysis:** To study the fundamental principles of **microwave propagation in rectangular waveguides**, including signal generation, modulation, and attenuation.
- **Measurement Techniques:** To develop practical skills in using microwave instruments such as **frequency meters and slotted line sections** to determine **operating frequency, wavelength, and Voltage Standing Wave Ratio (VSWR)**.
- **Mechanical Assembly:** To practice proper **waveguide assembly and flange connection techniques** in order to minimize signal loss and prevent microwave leakage.

---

## II. Materials and Components Used

### A. Power and Oscillation Modules

| Component | Description |
|-----------|-------------|
| **1 kHz Square-Wave Modulator** | A function generator that modulates the microwave signal with a low-frequency square wave. This modulation allows AC-coupled detection, improving measurement sensitivity. |
| **Gunn Power Supply (Model U-3000P)** | Provides a stable and low-noise DC bias required to operate the Gunn diode in its negative resistance region. |
| **Gunn Diode Oscillator** | The primary microwave signal source. It uses a **Gallium Arsenide (GaAs) diode** inside a resonant cavity to generate coherent microwave signals within the X-band frequency range. |

---

### B. Passive Transmission Components

| Component | Description |
|-----------|-------------|
| **Ferrite Isolator** | A non-reciprocal microwave device that allows signals to travel from the source to the load while absorbing reflected power, protecting the Gunn oscillator from damage. |
| **Directional Coupler (Multi-hole)** | Extracts a small portion of the signal (e.g., −10 dB or −20 dB) for monitoring without significantly affecting the main transmission path. |
| **E-Plane and H-Plane Bends** | Curved waveguide sections used to redirect microwave signals. The **E-plane bend** curves along the electric field, while the **H-plane bend** curves along the magnetic field. |
| **Variable Vane Attenuator** | A calibrated device that introduces controlled attenuation by inserting a resistive element into the waveguide, preventing detector overload. |

---

### C. Measurement and Analysis Equipment

| Component | Description |
|-----------|-------------|
| **Absorption Frequency Meter** | A high-Q resonant cavity instrument used to determine the operating frequency. It produces a noticeable signal dip when tuned to resonance. |
| **Slotted Line Section** | A precision waveguide section with a longitudinal slot that allows a movable probe to measure the standing wave pattern inside the guide. |
| **Tunable Detector Mount** | Contains a microwave detector diode (point-contact or Schottky diode) that converts high-frequency signals into measurable DC voltage. |

---

### D. Termination and Mechanical Components

| Component | Description |
|-----------|-------------|
| **Pyramidal Horn Antenna** | A directive antenna used to radiate microwave energy from the waveguide into free space. |
| **Matched Load (Termination)** | A specially designed absorber that eliminates reflections by absorbing nearly all incident microwave power. |
| **Movable Short Circuit** | A sliding metal plunger that creates a complete reflection, allowing measurement of standing wave minima and maxima. |
| **WR-90 Hardware Kit** | Includes mounting stands, flange screws, and alignment hardware necessary for assembling the waveguide system. |

---

## III. Procedure

### 1. Initial Bench Setup

1. Position the **Gunn power supply** and **Gunn oscillator** on the left side of the laboratory bench.
2. Inspect all **WR-90 waveguide flanges** to ensure they are clean and free from dust, oxidation, or physical damage that may cause signal leakage or arcing.

---

### 2. Waveguide Assembly

1. Connect the **Ferrite Isolator** directly to the output of the Gunn oscillator.
2. Attach the **Variable Attenuator**, initially set to maximum attenuation to prevent excessive power during startup.
3. Connect the **Absorption Frequency Meter** followed by the **Slotted Line Section**.
4. Secure each waveguide flange using the **cross-tightening method** to ensure uniform pressure and proper electrical contact.

---

### 3. Source Activation

1. Connect the **BNC cables** between the Gunn power supply and the oscillator module.
2. Gradually increase the bias voltage (typically **8–10 V**) until microwave oscillation begins.
3. Monitor the current to confirm stable operation of the Gunn diode.

---

### 4. Signal Modulation

1. Enable the **1 kHz square-wave modulation**.
2. This modulation allows the **VSWR meter or oscilloscope** to detect the signal more effectively by eliminating DC drift and improving signal clarity.

---

### 5. Frequency Measurement

1. Slowly adjust the **micrometer dial** on the absorption frequency meter.
2. Observe the detector output for a **sudden dip in signal strength**, indicating resonance.
3. Record the micrometer reading and convert it to **GHz** using the instrument’s calibration chart.

---

### 6. Standing Wave Measurement

1. Move the **probe carriage** along the slotted line section.
2. Identify the positions of **two consecutive voltage minima**.
3. Record these positions to calculate the **guide wavelength** using:

\[
\lambda_g = 2 \times |d_1 - d_2|
\]

where:

- \( d_1 \) = position of the first minimum  
- \( d_2 \) = position of the second minimum  

---

## IV. Results and Discussion

The experiment demonstrated the importance of proper **waveguide configuration and alignment** in microwave measurements. During frequency verification, the absorption frequency meter produced a **sharp resonance dip**, indicating high selectivity and accurate tuning of the resonant cavity.

In the **slotted line measurement**, the standing wave pattern inside the waveguide was clearly observed. By measuring the distance between successive voltage minima, the **guide wavelength (\(\lambda_g\))** was calculated. The results confirmed that the **guide wavelength is larger than the free-space wavelength (\(\lambda_0\))** due to wave reflections within the rectangular waveguide structure.

The **variable attenuator** played a critical role in protecting the detector diode from excessive power. Without proper attenuation, the detector could easily become saturated or damaged.

It was also observed that **improperly tightened flange connections** caused noticeable signal loss. This demonstrated that even small mechanical imperfections can lead to **microwave leakage and increased insertion loss**, particularly at X-band frequencies.

---

## V. Reflection / Learning Summary

This laboratory experiment provided valuable insight into the practical aspects of **microwave engineering**. Unlike conventional electronic circuits where signals travel through wires, microwave systems treat signals as **electromagnetic waves propagating within hollow waveguides**.

One of the most important lessons learned was the significance of **mechanical precision** in microwave systems. Proper alignment, cleanliness, and secure flange connections are essential to maintain signal integrity and minimize reflections.

The hands-on experience with instruments such as the **frequency meter and slotted line section** made theoretical concepts like **resonance, standing waves, and wave propagation** easier to understand. Observing these phenomena directly reinforced the idea that at microwave frequencies, **every physical discontinuity—such as gaps, bends, or misalignment—can act as an impedance mismatch**.

Overall, the experiment strengthened my understanding of **microwave transmission systems**, emphasizing the importance of both **electrical design and mechanical accuracy** in achieving efficient signal propagation.
<img width="794" height="607" alt="558953203-dce9bb2c-795d-44e2-8695-e8e206b44afd" src="https://github.com/user-attachments/assets/4001dcb9-c182-4ad7-be8e-aecbe516c002" />
<img width="763" height="611" alt="558953318-f9684d14-dc91-4c30-96a6-dcbaedcb3a2a" src="https://github.com/user-attachments/assets/ea8b87e8-bc3b-42d6-a59f-8dd4d07cd4a7" />

