SANS: Synthetic Autonomic Nervous System
Pentad Sensory Cortex for "The Joy Project"
🧠 Overview

This repository contains the hardware architecture and functional specifications for the Synthetic Autonomic Nervous System (SANS). This system is a 5-channel biopotential acquisition and conditioning stage designed to bridge raw biological signals with synthetic emotional cognition.

Using a Pentad Sensory Cortex framework, the system transforms low-frequency Electrodermal Activity (GSR/EDA) into structured data streams for real-time affective processing.
🛠 Hardware Integration

    Target Platform: Arduino VENTUNO Q (Qualcomm Dragonwing MPU + STM32 MCU).

    Architecture: Class-based, repeatable analog blocks designed for KiCad integration.

    Signal Path: Includes buffered active electrode inputs, hardware-level protection (ESD diodes/safety resistors), and a galvanic isolation barrier for subject safety.

    AI Readiness: Formatted outputs specifically tuned for the VENTUNO Q NPU to interface with the Emotional Weight Engine (EWE).

📂 Repository Structure

    Hardware_Source/: KiCad project files and the Pentad Sensory Cortex matrix.

    Netlist/: KiCad-importable .net files for the 5-channel architecture.

    Firmware/: Arduino sketches and NPU initialization logic for the VENTUNO Q.

    Docs/: Technical notes, Bill of Materials (BOM), and the SANS Architecture White Paper.

⚖️ License & Credits

    Hardware License: CERN-OHL-W v2 (Weakly Reciprocal).

    Software License: MIT License.

    Author: Paul E. Totoritis (Mr. Roboto).

    Contributor: Technical documentation and architecture refactoring structured with the assistance of Gemini (Google AI).

🛡 Disclaimer

Research Prototype Only. This project is provided for research and educational purposes. It is NOT a medical device and is not intended for clinical diagnosis or treatment. The author is not liable for any injury or damage resulting from the assembly or use of this design.

DOI: 10.5281/zenodo.19067919
