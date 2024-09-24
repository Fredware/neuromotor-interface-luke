# Advanced Neuromotor Interface for Prosthetic Hand Control (ANIPC) 
## Overview
This project contains code for a neuromotor interface system that enables real-time control of the LUKE arm, a dexterous robotic hand, using surface electromyography (EMG) signals from the Muscle SpikerShield bio-amplifier. 
The system integrates three key components:
1. Muscle SpikerShield (Backyard Brains Inc.): Samples surface EMG signals from muscles and transmits them to a PC via serial communication.
2. Matlab Decoder Script: Receives raw EMG signals, extracts features, and maps them to continuous commands for the LUKE arm.
3. LUKE Arm: A sensorized, dexterous robotic hand capable of multi-finger movement.
