Transformerless Power Supply – PCB Design (KiCad)

This repository contains the schematic, PCB layout, and 3D board view of a compact transformerless AC-to-DC power supply designed in KiCad 7/8/9.
The circuit uses a capacitive dropper, diode rectifier, Zener regulation, and filtering to provide a stable 5V DC output.

📁 Project Contents

schematic/ – KiCad schematic file (.kicad_sch)
pcb/ – PCB layout file (.kicad_pcb)
gerber/ – Manufacturing-ready Gerber files
3d_view/ – 3D renders of the completed PCB
README.md – Project documentation

⚡ Features

Transformerless AC to DC supply
Capacitive dropper input stage
Full-bridge rectification using 1N4007 diodes
Zener-based voltage regulation
Smoothing using electrolytic capacitors
On-board 5V output terminal
Compact single-sided PCB design
3D model preview included

🛠️ Components Used

Component	  Value / Part Number     	Description
C4	       225J / 2.2µF       	   X2 capacitor for AC dropper
R1	       4.7kΩ	                 Discharge/resistor
D1–D4	     1N4007	                 Bridge rectifier
C1	       0.1µF	                 Noise filter
C2	       1000µF	                Main smoothing capacitor
Zener	     5.1V / 6.2V	          Voltage regulation
C3	       470µF	                Output filter
U1	      Regulator (optional)  	Additional stabilization
J1 / J2	  Screw terminal	        AC input / DC output


🧩 Tools & Software

KiCad 9.0.6 (Schematic + PCB)
3D Viewer inside KiCad
Any Gerber viewer for fabrication checks

🖼️ Preview
✔️ Schematic
✔️ PCB Layout 
✔️ 3D Render

🏗️ How to Use

Open the project in KiCad.
Review/edit schematic as needed.
Generate new Gerber files if required:
File → Plot → Gerber
Upload the Gerbers to any PCB manufacturer (JLCPCB, PCBWay, etc.)
Solder components and test carefully with isolation and safety in mind.

⚠️ Safety Note

This design works directly with AC Mains, which is dangerous.
Use proper insulation, spacing, and testing precautions.
Only attempt this if you understand high-voltage safety.

📜 Author

Designed by Engineer Yoganshi
(PCB, Schematic & Layout)
