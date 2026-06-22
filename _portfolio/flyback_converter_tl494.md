---

title: "120W Flyback Converter Design Using TL494"
excerpt: >
  Designed and validated a 120W flyback converter to step up
  12V DC to 19.5V DC using the TL494 PWM controller.<br/>
  <img src="/images/flyback_converter/flyback_3d_view.png"
       style="width:500px; height:300px;"
       alt="Schematic">
collection: portfolio

---

## Overview

During my Erasmus exchange semester at South-West University, Bulgaria, I designed, simulated, and validated a high-power flyback converter based on the TL494 PWM controller.

The project focused on developing a compact and efficient DC-DC converter capable of converting a 12V input supply into a regulated 19.5V output while delivering up to 120W of power. The complete design process included theoretical calculations, circuit simulation, PCB design, hardware implementation, and performance evaluation.


## Objectives

* Design a flyback converter using the TL494 PWM controller
* Convert 11.1–12.6V DC input to a regulated 19.5V DC output
* Deliver up to 120W output power
* Operate at a switching frequency of 50 kHz
* Minimize output voltage ripple
* Validate the design through simulation and experimental testing


## Design Specifications

| Parameter               | Value                |
| ----------------------- | -------------------- |
| Input Voltage           | 11.1V – 12.6V        |
| Output Voltage          | 19.5V                |
| Maximum Output Current  | 10A                  |
| Output Power            | 120W                 |
| Switching Frequency     | 50 kHz               |
| Output Ripple           | 20 mV (peak-to-peak) |
| Inductor Current Ripple | 1.5A                 |


## Engineering Work

### Converter Design

The flyback topology was selected due to its simplicity, isolation capability, and suitability for medium-power DC-DC conversion.

The TL494 PWM controller was used to regulate the switching duty cycle and maintain a stable output voltage under varying load conditions.

### Simulation

The converter was analyzed and verified through circuit simulations in Proteus. Key operating parameters such as duty cycle, transformer operation, output regulation, and efficiency were evaluated.

### PCB Design

A custom PCB was designed in EasyEDA for the converter, considering:

* High-current traces
* Component placement optimization
* Switching noise reduction
* Thermal performance
* Manufacturability

### Hardware Validation

The fabricated PCB was assembled and tested under different operating conditions to verify:

* Output voltage regulation
* Converter efficiency
* Stability
* Thermal behavior
* Overall performance


## Results

The final prototype successfully achieved:

* Stable 19.5V regulated output
* 120W power delivery capability
* Reliable operation at 50 kHz
* Low output voltage ripple
* Good conversion efficiency
* Consistent performance across varying loads

The project demonstrated the practicality of using the TL494 controller for high-power flyback converter applications while maintaining compact size and efficient operation.


## Gallery

### Schematic

<img src="/images/flyback_converter/flyback_schematic.png"
       style="width:500px; height:auto;"
       alt="Schematic">

### PCB Layout

<img src="/images/flyback_converter/flyback_pcb_layout.png"
       style="width:500px; height:auto;"
       alt="PCB Layout">

### 3D PCB View

<img src="/images/flyback_converter/flyback_3d_view.png"
       style="width:500px; height:auto;"
       alt="3D PCB View">


## Skills Demonstrated

* Power Electronics
* DC-DC Converter Design
* Flyback Converter Topology
* TL494 PWM Controller
* PCB Design
* Electronic Circuit Simulation
* Hardware Testing
* Embedded Hardware Development
* Engineering Documentation

---

**Institution:** South-West University, Bulgaria<br>
**Program:** Erasmus Exchange Program<br>
**Project Type:** Power Electronics Design Project<br>
