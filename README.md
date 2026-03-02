# CNC Machine Design & Build - *In Progress*

<p align="center">
  <a href="https://github.com/DanielOkhman/Daniel-Okhman">
    ← Back to Main Portfolio
  </a>
</p>

---

## Objective

The objective of this project is to design and build a functional CNC machine in order to deepen my understanding of motion control systems, electromechanical integration, and computer-controlled manufacturing.  

Rather than purchasing a prebuilt kit, I chose to engineer the system myself — configuring stepper motors, looking into GRBL parameters, assembling the mechanical frame, and validating smooth, repeatable motion. The long-term goal is to integrate a spindle and transition from simply motion to precision cutting.

---

**Status:** Smooth motion, jogging, consistent travel, repeatable positioning 

**Next:** Spindle + mount, cable management/drag chain, first test cuts

---

## Demo Video

**Smooth motion + GRBL control demo:**  
[![CNC Build Demo (YouTube)](https://img.youtube.com/vi/yPvveoob8fM/hqdefault.jpg)](https://www.youtube.com/watch?v=yPvveoob8fM)

---

## Build Photos

<table>
<tr>
<td align="center">
<img src="https://github.com/DanielOkhman/Brushless-DC-Motor-Design-and-Build/blob/6a934d01ce711f70aa0d2500dbf3b0ae6c0a002c/IMG_6542.jpeg" width="400"/><br>
</td>

<td align="center">
<img src="https://github.com/DanielOkhman/Brushless-DC-Motor-Design-and-Build/blob/85935705922fd17cd7e72fb91e2abe28dd3aee59/IMG_6538.jpeg" width="400"/><br>
</td>
</tr>
</table>

---

## Skills Learned

- **Motion control + CNC fundamentals:** setting steps/mm, direction, acceleration, max feed rates, and understanding how these affect smoothness and missed steps  
- **GRBL workflow:** jogging, sending G-code, verifying travel, and iterating configuration ($-settings) for stable motion  
- **Stepper motor integration:** wiring, coil pairing, current limits (to reduce overheating and missed steps), and basic torque/speed tradeoffs  
- **Electromechanical debugging:** diagnosing vibration, stalling, binding, and wiring issues using systematic tests and incremental changes  
- **Mechanical build iteration:** squaring the frame, aligning rails, checking rigidity, and learning how small misalignments show up as motion artifacts  
- **Project execution:** breaking a complex build into milestones (motion → control → spindle → first cuts) and documenting progress clearly

---

## Tools Used

**Hardware**
- Stepper motors (X/Y axes; Z planned/optional depending on design)
- Arduino + motor shield (GRBL controller)
- CNC frame components (extrusions/frame members, linear motion components, fasteners)
- Power supply (sized for steppers/shield)

**Software**
- **GRBL** (firmware / motion control)
- G-code sender on laptop (e.g., Universal Gcode Sender / Candle / similar)
- (Optional) CAD/CAM for future cutting workflow (Fusion 360, etc.)

**General shop / build tools**
- Hex keys, screwdrivers, measuring tools (tape measure, square/calipers)
- Basic electrical tools (wire stripper, crimper, ferrules/connectors as needed)

---

## Steps Taken (Build Timeline)

1. **Defined requirements + layout**
   - Chose work area size, axis layout, and frame approach (rigidity vs. simplicity)

2. **Assembled mechanical frame**
   - Built base frame and gantry structure  
   - Confirmed squareness and tightened in a controlled sequence

3. **Installed motion components**
   - Mounted linear motion parts and verified free travel by hand  
   - Corrected binding/alignment issues before powering motors

4. **Integrated stepper motors**
   - Mounted motors and coupled to drive mechanism  
   - Verified correct coil pairing + direction for each axis

5. **Controller + wiring**
   - Wired Arduino + motor shield to motors and power supply  
   - Cleaned up wiring enough to test safely (more cable management planned)

6. **GRBL setup + configuration**
   - Flashed/confirmed GRBL  
   - Tuned key parameters: steps/mm, feed rate, acceleration, direction, (optional) homing/limits

7. **Motion validation**
   - Performed repeatable jog tests across the full working range  
   - Adjusted acceleration/current/velocity to eliminate missed steps and reduce vibration

8. **Current milestone achieved**
   - **Smooth movement demo recorded** and uploaded (see video above)

---

## Next Steps

- Add **spindle + mount** (and consider dust shoe planning early)
- Implement/verify **limit switches + homing** (if not already done)
- Improve **cable management** (drag chain, strain relief, routing)
- Add/finish **Z-axis** (if part of your final design) and test under load
- Run first “cutting” workflow:
  - pen plotter test → foam test → wood test
- Document calibration results (repeatability, backlash checks, squareness)

---
<p align="center">
  <a href="https://github.com/DanielOkhman/Daniel-Okhman">
    ← Back to Main Portfolio
  </a>
</p>
