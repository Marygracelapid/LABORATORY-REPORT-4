# Experiment 21: Antenna Trainer Kit

## I. Objectives

The objectives of this experiment are:

- **Radiation Pattern Mapping:** To experimentally determine and plot the **two-dimensional radiation patterns** of both resonant and non-resonant antennas using a **polar coordinate system**.
- **Parameter Evaluation:** To measure and compare important antenna characteristics such as **gain, directivity, front-to-back ratio, and half-power beamwidth (HPBW)**.
- **Array Analysis:** To examine how **parasitic elements in Yagi-Uda arrays** and **element phasing in antenna arrays** influence the distribution and concentration of electromagnetic radiation.
- **Impedance Matching:** To demonstrate the practical use of **matching stubs** in reducing **standing wave ratio (SWR)** and improving **power transfer efficiency**.
<img width="636" height="383" alt="558960110-5c512238-7192-4eef-8b9e-78a56d5fa417" src="https://github.com/user-attachments/assets/893a0726-5bde-4606-b30a-e589a33388c5" />

---

## II. Materials and Components Used

### System Equipment

| Equipment | Description |
|-----------|-------------|
| **Master Antenna Trainer Unit** | Serves as the central control unit, providing a regulated RF signal source (typically VHF/UHF), modulation control, and signal strength monitoring through a built-in display. |
<img width="425" height="212" alt="558960355-2f75de63-3d81-4bb4-a806-6f1833509940" src="https://github.com/user-attachments/assets/ac7cb2b4-7b94-44b0-b139-9a22dc2942e7" />

| **Matching Stub** | A transmission-line tuning device used to compensate for reactive components and match the antenna impedance to the feeder line. |
<img width="215" height="606" alt="558960678-01f1c54d-f582-42fb-bfa2-0d508bc57860" src="https://github.com/user-attachments/assets/84659029-79c2-4aed-8e08-86aa053c74b5" />

| **Transmitting Mast** | A rotatable mounting structure with a **360° angular scale** used to adjust the orientation of the transmitting antenna. |
<img width="455" height="555" alt="558960427-4b4b18e1-4543-4fa9-ab4e-571bf246fbd4" src="https://github.com/user-attachments/assets/7fbdee09-0427-4e83-b63b-553ba4d9e490" />

| **Receiving Mast** | A fixed support that holds the receiving antenna or detector probe at a constant distance to maintain **far-field measurement conditions**. |
<img width="459" height="324" alt="558960507-63fb2245-e9a5-44d7-9471-780fe950b3dd" src="https://github.com/user-attachments/assets/0ea4d2ce-94b6-4e7e-8d99-40eaa78ecfbd" />

| **RF Detector** | A high-sensitivity rectifier circuit that converts received RF energy into a measurable **DC signal**. |
<img width="409" height="512" alt="558960579-b7b182d3-61a4-46e3-8f0a-1c3f165fe0ee" src="https://github.com/user-attachments/assets/afb9ce27-e0d7-45db-8fdd-35f5ab241c55" />

---

### Antenna Elements Used in the Trainer Kit

| Antenna Type | Description |
|---------------|-------------|
| **Detector Antenna** | A compact probe used to measure the electromagnetic field strength without significantly disturbing the radiation pattern. |
<img width="222" height="746" alt="558957753-fff51865-aeca-4fa1-bfe4-8c7b450aa820" src="https://github.com/user-attachments/assets/e02386ec-3f27-43ca-be11-1fe5619f4c32" />

| **Slot Antenna (λ/2)** | A slot cut into a conductive surface. Based on **Babinet’s Principle**, it radiates similarly to a dipole but with polarization perpendicular to the slot orientation. |
<img width="270" height="125" alt="558957968-8c450921-6703-4405-8224-059b74f15747" src="https://github.com/user-attachments/assets/bbdd3e1a-dd85-482b-bc52-0db3b1f40cc4" />

| **Helix Antenna** | A spiral-shaped conductor capable of producing **circular polarization** in axial mode, commonly used in satellite communications. |
<img width="326" height="352" alt="558957863-c443a311-0649-476d-9c76-0291d2b53cbc" src="https://github.com/user-attachments/assets/436b9c1c-0563-4498-b722-abc69fd45d44" />

| **Yagi-Uda Folded Dipole (3-Element)** | A directional array consisting of a folded dipole driver, one reflector, and one director. |
<img width="328" height="533" alt="558957601-158dc70c-cf14-4a5e-8636-b60b226921cc" src="https://github.com/user-attachments/assets/882e953e-39d3-4d78-a9f5-91f7cb138a51" />

| **Yagi-Uda Folded Dipole (5-Element)** | A larger Yagi array with additional directors that increases forward gain and narrows the main beam. |
<img width="345" height="322" alt="558956841-0ce972a8-2fb9-4857-bb5c-bce647e049d6" src="https://github.com/user-attachments/assets/23a28c6f-1750-409b-962c-f6e82d11563a" />

| **Yagi-Uda Simple Dipole (5-Element)** | A Yagi array using a straight dipole driver, offering strong gain but generally narrower bandwidth. |
<img width="350" height="501" alt="558957006-0eba28e5-f599-4470-b2f9-0b52947881cd" src="https://github.com/user-attachments/assets/30386ffe-fed7-4c3e-90e9-735aeaa52da9" />

| **Yagi-Uda Simple Dipole (7-Element)** | A high-directivity array with multiple directors designed for long-distance point-to-point communication. |
<img width="332" height="592" alt="558957086-d7331c2a-1e38-4c11-a1d1-84f20e5da236" src="https://github.com/user-attachments/assets/d44280bb-60b7-4d07-a867-bad7566cf731" />

| **Simple Dipole (3λ/2)** | A harmonic long-wire antenna that generates multiple lobes and nulls in its radiation pattern. |
<img width="302" height="121" alt="558958201-0e7d9a58-32fd-46c4-8535-9c40655a21df" src="https://github.com/user-attachments/assets/5b6c1c29-b1b2-4f8f-a79a-e6b9adaa3708" />

| **Folded Dipole (λ/2)** | A dipole configuration where the conductor is folded back on itself, increasing input impedance and bandwidth. |
<img width="240" height="99" alt="558957456-bb9fa79c-460b-4fcc-a7b3-7bc4d6f3fa55" src="https://github.com/user-attachments/assets/c9fd1482-b6d0-4afe-8442-09952752d6d3" />

| **Simple Dipole (λ/2)** | A resonant half-wave antenna that produces an omnidirectional **toroidal radiation pattern** perpendicular to the conductor. |
<img width="347" height="240" alt="558957360-dcf02e93-5b30-4fa6-a3b0-6ce7afac4e67" src="https://github.com/user-attachments/assets/c1a7b63f-c96e-4efb-944d-50fa27981e1f" />

| **Simple Dipole (λ/4)** | A monopole-type antenna typically used with a **ground plane** to simulate the other half of the dipole. |
<img width="335" height="299" alt="558958323-598c7c3a-28e5-41bd-98af-db284af1d334" src="https://github.com/user-attachments/assets/4819a05b-d96e-4efd-bfa4-f057116a7666" />

| **Zeppelin (Zepp) Antenna** | An end-fed half-wave antenna traditionally used in airship communications. |
<img width="305" height="88" alt="558958520-9a078713-9c4e-4ba6-aff3-aefed913a8ef" src="https://github.com/user-attachments/assets/a8565f59-26a1-43c4-8443-fa8432e0f0b3" />

| **Hertz Antenna** | A basic balanced antenna system, typically referring to dipole-type radiators that do not rely on ground conduction. |
<img width="284" height="120" alt="558958489-2a8f602d-2565-4860-8d46-dac148e1f623" src="https://github.com/user-attachments/assets/4ed90638-5fc8-4aea-8eb1-eb8a3c65392f" />

| **Combined Collinear Array** | A vertically stacked arrangement of dipoles designed to increase **omnidirectional gain along the horizon**. |
<img width="297" height="497" alt="558958704-56fd9a70-fc15-4556-9f6e-19188dc46a0a" src="https://github.com/user-attachments/assets/84e7cd82-9f4d-4813-ace1-5eba9c59d811" />

| **λ/2 Phase Array** | Two dipole elements spaced half a wavelength apart, producing interference patterns depending on feed phase. |
<img width="279" height="244" alt="558958565-4966379a-c85e-4b6d-80ab-80e1ee91ac2c" src="https://github.com/user-attachments/assets/6a4d394d-d71e-4d1f-a6b9-786c0e485ed0" />

| **λ/4 Phase Array** | An array with quarter-wavelength spacing, commonly used to produce **end-fire radiation patterns**. |
<img width="296" height="515" alt="558958605-8658a008-ec3b-4ba0-a747-5bf36410b7a3" src="https://github.com/user-attachments/assets/2796ee4c-f269-4028-8489-7cbc6c8b3442" />

| **Cut Paraboloid Antenna** | A reflector antenna that uses a curved surface to focus electromagnetic waves into a highly directional beam. |
<img width="345" height="274" alt="558958867-46accbfa-af90-48b4-8636-33262fb78af4" src="https://github.com/user-attachments/assets/e9a6cfad-cc06-4916-8cf0-ba6fd8689853" />

| **Broadside Array** | Multiple antenna elements fed in phase to generate a strong radiation lobe perpendicular to the array axis. |
<img width="343" height="227" alt="558958740-eafabf15-cfe7-45ef-9251-e404cea09b10" src="https://github.com/user-attachments/assets/d81c0623-7075-41d7-9fcc-b1849398efac" />

| **Loop Antenna** | A closed conductor loop acting primarily as a **magnetic dipole**, effective in reducing electrical noise. |
<img width="329" height="306" alt="558958905-d206fe39-cda3-4a63-aa3e-d20c4f9fe18d" src="https://github.com/user-attachments/assets/cd751011-ef70-4d2a-980a-7b698d8376e2" />

| **Log Periodic Antenna** | A broadband directional antenna with logarithmically scaled elements to maintain consistent performance across a wide frequency range. |
<img width="338" height="679" alt="558958793-4ff82e7a-5593-4ceb-972e-7b02dcd4551b" src="https://github.com/user-attachments/assets/30ad6a95-db8d-4805-b088-6af5781837e3" />

| **Ground Plane Antenna** | A vertical radiator supported by radial conductors that simulate an artificial ground surface. |
<img width="343" height="296" alt="558959114-8c49b34e-e4ab-4fcd-b386-b6a5ac4a7348" src="https://github.com/user-attachments/assets/ef6fc240-6444-4e55-ae45-7feefbfdc010" />

| **Rhombus Antenna** | A large non-resonant wire antenna with a diamond shape, widely used for **high-frequency long-distance communication**. |
<img width="291" height="247" alt="558959053-8f1a3ce2-2e96-4fad-8249-bf0a4a9b2b67" src="https://github.com/user-attachments/assets/5c88ec4d-d991-4282-934f-4aca7daf3ae6" />

---

## III. Procedure

### A. Initial System Setup

1. Place the **transmitting mast** and **receiving mast** on a stable surface with a separation of approximately **1 to 1.5 meters** to ensure measurements occur in the **far-field region**.
2. Connect the **RF output** of the antenna trainer unit to the **matching stub**, and then connect the stub output to the **transmitting mast**.
3. Mount the **detector antenna** on the receiving mast.
4. Connect the detector output to the **signal strength input** of the trainer unit.

---

### B. Impedance Matching Calibration

1. Install the **Simple Dipole (λ/2)** antenna on the transmitting mast.
2. Turn on the antenna trainer unit.
3. Adjust the **sliding section of the matching stub** gradually.
4. Observe the **SWR or signal strength meter** and stop adjusting once the **maximum signal level** is obtained, indicating proper impedance matching.

---

### C. Radiation Pattern Measurement

1. Align the transmitting antenna to the **0° reference position (boresight)**.
2. Adjust the trainer’s **gain or range control** until the meter displays a full-scale reference reading.
3. Rotate the transmitting mast in **10° increments**.
4. At each position, allow the meter to stabilize and **record the signal strength**.
5. Continue rotating until a **complete 360° radiation pattern** is measured.

---

### D. Comparative Antenna Testing

1. Replace the **half-wave dipole** with the **7-element Yagi-Uda antenna**.
2. Without changing the separation distance, repeat the **360° measurement procedure**.
3. Conduct a **polarization test** by rotating the receiving antenna **90°** to observe the signal reduction caused by **cross-polarization**.

---

## IV. Results and Discussion

The experimental measurements clearly demonstrated the differences in radiation characteristics among various antenna types.

The **half-wave dipole antenna** produced the expected **figure-eight radiation pattern**, radiating energy nearly equally in the forward and backward directions. This pattern confirmed its characteristic omnidirectional behavior in the horizontal plane.

In contrast, the **Yagi-Uda antenna arrays** produced a significantly more **directional radiation pattern**. As the number of director elements increased, the main radiation lobe became narrower and more concentrated.

Key observations include:

- **Gain vs. Number of Elements:**  
  The **7-element Yagi-Uda antenna** exhibited significantly higher peak radiation intensity at the **0° direction** compared to the **3-element configuration**.

- **Front-to-Back Ratio:**  
  The presence of the **reflector element** effectively reduced radiation toward the rear (around **180°**), resulting in stronger forward radiation.

- **Polarization Effects:**  
  When the transmitting antenna was vertically oriented and the receiving antenna was rotated horizontally, the measured signal strength dropped by more than **20 dB**. This confirmed the importance of **matching polarization** in wireless communication systems.

---

## V. Reflection / Learning Summary

This experiment provided a practical visualization of how **electromagnetic radiation patterns** behave in real antenna systems. It reinforced the concept that antennas function not only as radiators but also as **spatial filters that shape electromagnetic energy in specific directions**.

One of the most notable observations was the role of **parasitic elements in the Yagi-Uda antenna**. Although these elements are not directly connected to the power source, they significantly modify the radiation pattern through **mutual coupling and phase interactions**.

The experiment also highlighted the importance of **impedance matching** using the matching stub. Proper impedance matching ensures that maximum power is transferred from the transmitter to the antenna. Without proper matching, even a high-gain antenna can perform inefficiently due to reflections along the transmission line.

Overall, this laboratory activity provided valuable insights into **antenna design, radiation behavior, and RF system optimization**, which are essential concepts in modern **wireless communication and RF engineering**.
