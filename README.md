# CNC Machine Design & Build - *In Progress*

<p align="center">
  <a href="https://github.com/DanielOkhman/Daniel-Okhman">
    ← Back to Main Portfolio
  </a>
</p>

---

## Objective

The objective of this project is to design and build a functional CNC machine in order to deepen my understanding of motion control systems, electromechanical integration, and computer-controlled manufacturing.  

Rather than purchasing a prebuilt kit, I chose to engineer the system myself which included: configuring stepper motors, looking into GRBL parameters, assembling the mechanical frame, and validating smooth, repeatable motion. The long-term goal is to integrate a spindle and transition from isolated motion to precision cutting.

---

**Status:** Smooth motion, jogging, consistent travel, repeatable positioning 

**Next:** Spindle, cable management/drag chain, first test cuts

---

## Demo Video

**Smooth motion and GRBL control demo:**  

<p align="center">
  <a href="https://www.youtube.com/watch?v=yPvveoob8fM">
    <img src="https://img.youtube.com/vi/yPvveoob8fM/hqdefault.jpg"
         alt="CNC motion demo video"
         width="400">
  </a>
</p>

<p align="center">
  <i>Click image to watch demo video ↗</i>
</p>

---

## Build Photos

<table>
<tr>
<td align="center">
<img src="https://github.com/DanielOkhman/CNC-Machine-Design-Build/blob/8fa8024044576af72d63a2afc24f604502b99ea2/IMG_7027.jpg" width="400"/><br>
</td>

<td align="center">
<img src="https://github.com/DanielOkhman/CNC-Machine-Design-Build/blob/158e4e399a0d1d52271278f9f2894feb8d282817/IMG_7029.jpg" width="400"/><br>
</td>
</tr>
</table>

---

## Skills Learned

- **Motion control:** setting steps/mm, direction, acceleration, max feed rates, and understanding how these affect smoothness and missed steps  
- **GRBL workflow:** jogging, converting CAD to G-code, sending G-code
- **Stepper motor integration:** wiring, coil pairing and basic torque/speed tradeoffs  
- **Electromechanical debugging:** diagnosing vibration, stalling, and wiring issues using systematic tests and incremental changes  
- **Mechanical build iteration:** squaring the frame, aligning rails and checking rigidity
- **Project execution:** breaking a complex build into sections: motion, control, spindle

---

## Tools Used

**Hardware**
- Stepper motors (X/Y axes; Z in progress)
- Arduino and motor shield as GRBL controller
- CNC frame components
- Power supply

**Software**
- **GRBL** (firmware / motion control)
- G-code sender on laptop via Universal Gcode Sender
- CAD for future cutting (Fusion 360, Aspire.)

---

## Next Steps

- Add spindle 
- Implement/verify limit switches and homing 
- Improve cable management with a drag chain
- Add/finish Z-axis
- Run first cut

---
<p align="center">
  <a href="https://github.com/DanielOkhman/Daniel-Okhman">
    ← Back to Main Portfolio
  </a>
</p>
