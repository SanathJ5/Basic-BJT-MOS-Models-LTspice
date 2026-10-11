# Simple SPICE MOSFET and BJT Models

An editable library of basic MOSFET and BJT subcircuits designed specifically for academic coursework, introductory VLSI/circuit design, and rapid SPICE simulation.

## Editable model parameters

<img width="1291" height="924" alt="image" src="https://github.com/user-attachments/assets/50aa9733-dc04-420b-bb4b-db9553659dfd" />




| Parameter | Description | Default (Simple_NMOS) | Default (Simple_PMOS) |
| :--- | :--- | :--- | :--- |
| `vth` | Threshold Voltage | 1 V | -1 V |
| `kp` | Transconductance Parameter | 100 µA/V² | 100 µA/V² |
| `w` | Channel Width | 100 µm | 100 µm |
| `l` | Channel Length | 10 µm | 10 µm |
| `lam` | Channel-Length Modulation | 0 | 0 |
| `rd` | Drain Parasitic Resistance | 0 Ω | 0 Ω |
| `rs` | Source Parasitic Resistance | 0 Ω | 0 Ω |

<img width="924" height="755" alt="image" src="https://github.com/user-attachments/assets/207fc995-69c9-43bb-a6bf-927eac609259" />

##  Quick Start Guide

1. Clone this repo and extract the sym folder to Documents\LTspice\lib\  
2. Open LTspice, press P for adding components, search for [lib] and select the appropriate transistor  
3. Right clicking the symbol will allow you to change the parameters   
4. Thats all! Thank you  


##  Academic Purpose

This library was created to bridge the gap between theoretical textbook equations and practical circuit simulation. This library has only the essential textbook parameters so you can verify your calculations using DC sweeps, transient response, and AC small-signal analysis.

##  Contributing & Support

Feel free to fork, open issues, or submit pull requests if you have suggestions for enhancements or educational extensions.

##  License

This project is open-source and free to use for educational and academic purposes under the MIT License.
