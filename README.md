# TinyLAB: TinyLDOP
TinyLAB is a project that was created from the idea of enabling hobbyists and engineers to have the necessary electronic equipment for their projects without the need of buying expensive and bulky equipment.

TinyLDOP is the first part of this project and its purpose is to generate additional (low current) voltage rails from a single power supply.

It designed to be placed at the middle part of a breadboard as shown:

<img width="490" alt="tiny_LDOP_breadboard" src="https://github.com/user-attachments/assets/f95d3907-ff36-4e7b-826b-2feead970cd0">

# Specifications
Considering the typical supply voltages of electronic systems, we will set the output voltage range to 1.8 – 12 V. 

According to the LM317M datasheet, the difference between input and output voltage can be as low as 2.5 V. Therefore, the input voltage range must be 4.3 – 14.5 V (which we will round to 5 – 15 V)

The maximum output current depends on the input-output voltage difference and the maximum power the device is able to dissipate. Taking into account the worst case: input voltage equal to 15 V, output voltage equal to 1.8 V and considering the package is able to dissipate 750 mW with a small heatsink, the maximum output current is 57 mA, which we will round to 50 mA.
| Specification       | Value                      |
|---------------|----------------------------------|
| Input voltage range [V]  | 5–15 |
| Output voltage range [V]        | 1.8–12  |
| Maximum output current [mA]         | 50  |

