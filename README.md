# TinyLAB: TinyLDOP

![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat&logo=kicad&logoColor=white)

TinyLDOP is a breadboard-compatible linear regulator PCB for generating additional low-current voltage rails from a single power supply. It designed to be placed at the middle part of a breadboard as shown:

<img width="490" alt="tiny_LDOP_breadboard" src="https://github.com/user-attachments/assets/f95d3907-ff36-4e7b-826b-2feead970cd0">

---
# **Specifications**
Considering the typical supply voltages of electronic systems, we will set the output voltage range to 1.8 – 12 V. 

According to the LM317M datasheet, the difference between input and output voltage can be as low as 2.5 V. Therefore, the input voltage range must be 4.3 – 14.5 V (which we will round to 5 – 15 V)

The maximum output current depends on the input-output voltage difference and the maximum power the device is able to dissipate. Taking into account the worst case: input voltage equal to 15 V, output voltage equal to 1.8 V and considering the package is able to dissipate 750 mW with a small heatsink, the maximum output current is 57 mA, which we will round to 50 mA.

| Specification       | Value                      |
|---------------|----------------------------------|
| Input voltage range [V]  | 5–15 |
| Output voltage range [V]        | 1.8–12  |
| Maximum output current [mA]         | 50  |

---
## **License**
This project is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

You are free to:
- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material

Under the following terms:
- **Attribution** — You must give appropriate credit
- **NonCommercial** — You may not use the material for commercial purposes
- **ShareAlike** — Derivatives must use the same license

See the [LICENSE](LICENSE) file for the full license text.

---
## Author

[Miquel Tutusaus](https://github.com/mtutusaus), 2024
