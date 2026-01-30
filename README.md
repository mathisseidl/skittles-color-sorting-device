**🎨 Skittles Color Sorting Device 🎨**

<br/>

__Overview__

This project is a **low-cost, portable, and accessible** candy color sorting device designed to automatically sort Skittles into five colors: **Red, Yellow, Green, Orange, and Purple**.
A key design goal was **accessibility**, the device can be used by **color-blind and visually impaired users**, featuring **engraved labels and Braille markings** for each output compartment.

<br/>

  __How It Works__

1. Skittles are dropped into the funnel

2. A rotating disc moves the Skittle to the sensing position

3. The TCS3200 sensor takes multiple RGB readings

4. Next, the rotating disc aligns the Skittle with the ramp opening
   
6. A servo-controlled ramp guides the candy into the correct bin

7. System resets for the next cycle

<br/>

__Key Features:__

- Sorts 5 colors (Red, Yellow, Green, Orange, Purple)

- 100% accuracy across 100 trials

- Fast operation (~3 seconds per Skittle)

- Accessible design (Braille + engraved labels)

- Fully portable (battery-powered)

- Modular & serviceable (17 custom 3D-printed parts)

  <br/>

__Hardware components__

- Arduino Uno – main controller

- TCS3200 RGB Color Sensor – color detection

- MG996R Servo Motor – candy transport disc

- S51 Micro Servo – ramp positioning

- Vibration Motors – clog prevention

- Power Supply

  - 4× AA batteries (servos)

  - 9V battery + buck converter (Arduino)

  <br/>

__Mechanical Design__

- Wooden base for lightweight structure and laser engraving

- Large funnel capacity (~50 Skittles)

- Five individual storage compartments

- 17 custom 3D-printed parts (PLA)

<br/>

__CAD & Manufacturing__

- Designed for easy assembly and maintenance

- All parts mounted with screws (no glue)

- Washable 3D-printed components

- Optimized geometry for Skittle dimensions

<br/>

__Performance Metrics__


| Metric                   | Result                 |
| ------------------------ | ---------------------- |
| Sorting Accuracy         | **100%**               |
| Color Detection Accuracy | **100% (sensor)**      |
| Avg. Sorting Time        | **2.99 s**             |
| Device Weight            | **1.26 kg**            |
| Device Size              | **300 × 300 × 210 mm** |
| Battery Life             | **~9 hours**           |
| Total Cost               | **$58.47**             |

<br/>

__Lessons Learned__

- Servo motors provided far better reliability than stepper motors

- Black sensor background significantly improved color accuracy

- Real user testing is critical for intuitive interaction

<br/>
