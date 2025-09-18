This project involves designing a simple transformerless power supply using KiCAD. The circuit takes standard AC mains input (e.g., 120V/230V) and provides a low-voltage DC output suitable for powering small electronic circuits.

Instead of a bulky transformer, the design uses a capacitive dropper circuit consisting of:

- Capacitor (X-rated safety capacitor) – reduces the AC voltage.

- Resistors – limit inrush current and discharge the capacitor.

- Diodes – form a bridge rectifier to convert AC to DC.

- Zener diode or regulator – stabilizes the output voltage.

- Filter capacitor – smooths out the DC signal.
