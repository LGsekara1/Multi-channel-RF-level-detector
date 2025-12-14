# Multilevel RF Power Detector
**Dual-Band 433 MHz / 915 MHz RF Presence Indicator**

---

## General Description

The **Multilevel RF Power Detector** is a compact dual-band RF sensing device designed to detect and visually indicate the relative power of radio-frequency signals in the **433 MHz** and **915 MHz** ISM bands. The system employs band-pass filtering, low-noise amplification, and logarithmic detection to provide reliable RF presence indication using a multi-level LED display.

The device is intended for educational, laboratory, and experimental RF applications where quick visual feedback is required without the use of complex RF measurement equipment.

---

## Key Features

- Dual-band RF detection: 433 MHz and 915 MHz
- Logarithmic RF power detection
- Multi-level LED signal strength indication
- RF-optimized PCB layout
- Single DC supply operation
- Compact and portable design

---

## Applications

- ISM band signal monitoring
- RF laboratory demonstrations
- Educational RF experiments
- RF activity detection
- Wireless system debugging

---

## Functional Block Diagram

![Block Diagram](media/schematic_page18.jpg)

---

## Electrical Characteristics

| Parameter | Typical Value |
|---------|---------------|
| Supported Frequency Bands | 433 MHz, 915 MHz |
| Input Impedance | 50 Ω |
| LNA Gain | 433 MHz: 20.3 dB<br>915 MHz: 17.9 dB |
| Noise Figure | 433 MHz: 2.3 dB<br>915 MHz: 2.8 dB |
| Supply Voltage (Nominal) | 9 V |
| Supply Current | 200 mA |

---

## LED Signal Indication

| LED Status | RF Power Level (Relative) |
|-----------|---------------------------|
| 1 LED ON | Very Low |
| 2–3 LEDs ON | Low to Medium |
| 4–5 LEDs ON | Medium to High |
| All LEDs ON | High RF Power |

---

## Power Supply

- Single DC supply operation
- On-board voltage regulation

---

## Mechanical Information

| Parameter | Specification |
|---------|---------------|
| PCB Dimensions | 126.37 mm × 129 mm |
| Antenna Connector | SMA Edge-Mount |
| Enclosure | Custom Enclosure |

---

## Mechanical Drawings

**Mechanical Drawing – Page 1**  
![Mechanical Drawing Page 1](media/AnalogProject-page1.png)

**Mechanical Drawing – Page 2 (Assembly Views)**  
![Mechanical Drawing Page 2](media/AnalogProject-page2.png)

---

## Schematics

### 433 MHz Section
![433 MHz Schematic](media/schematic_page1.png)

### 433 MHz LNA Design
![433 MHz LNA](media/schematic_page2.png)

### LED Driver Circuit
![LED Driver](media/schematic_page3.png)

### Log Detector Circuit
![Log Detector](media/schematic_page4.png)

### 433 MHz Band-Pass Filter
![433 MHz BPF](media/schematic_page5.png)

### 915 MHz Section
![915 MHz Schematic](media/schematic_page6.png)

### 915 MHz LNA Design
![915 MHz LNA](media/schematic_page7.png)

### Power Supply Design
![Power Supply](media/schematic_page8.png)

---

## PCB Layout

### Top Layer
![Top Layer](media/schematic_page9.jpg)

### RF Ground Layer (Layer 2)
![RF GND Layer](media/schematic_page14.jpg)

### PCB Ground Layer (Layer 3)
![PCB GND Layer](media/schematic_page10.jpg)

### Bottom Layer
![Bottom Layer](media/schematic_page11.jpg)

### PCB Stack-Up
![PCB Stackup](media/schematic_page12.jpg)

### 3D PCB View
![3D View](media/schematic_page13.jpg)

---

## Frequency Response

### 433 MHz Band
![433 MHz Response](media/schematic_page15.png)

### 915 MHz Band
![915 MHz Response](media/schematic_page16.png)

---

## Final Product

![Final Product](media/schematic_page17.jpg)

---

## Handling and Precautions

- Device contains ESD-sensitive RF components
- Avoid hot-plugging the antenna
- Do not exceed the maximum supply voltage
- Use only matched SMA antennas

---

## Disclaimer

This product is intended for educational and experimental use only. It is not a calibrated RF power measurement instrument. Specifications are subject to change without notice.

---

**Department of Electronic & Telecommunication Engineering**  
**University of Moratuwa, Sri Lanka**

