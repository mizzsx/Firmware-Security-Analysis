# Firmware Security Analysis

![Linux](https://img.shields.io/badge/Linux-Environment-black)
![Ghidra](https://img.shields.io/badge/Ghidra-Reverse%20Engineering-red)
![Binwalk](https://img.shields.io/badge/Binwalk-Firmware%20Analysis-blue)
![Security](https://img.shields.io/badge/Security-Static%20Analysis-green)

## Overview

A practical firmware security lab focused on firmware extraction, static binary analysis, and reverse engineering.

The objective is to identify security weaknesses within embedded firmware and understand binary behavior without executing the target program.

## Tools & Technologies

- Linux
- Binwalk
- Ghidra
- Strings
- Grep
- ELF Binary Analysis

## Analysis Workflow

1. Identify the firmware file format.
2. Extract the firmware contents.
3. Examine configuration files.
4. Identify suspicious strings and hardcoded credentials.
5. Analyze binary functions and authentication logic.
6. Document security findings.

## Key Findings

- Identified a CPIO firmware archive.
- Discovered hardcoded laboratory credentials.
- Identified a Linux ELF binary.
- Examined authentication logic and strcmp() comparisons.
- Identified access-granted and access-denied execution paths.

## Repository Structure

    Firmware-Security-Analysis/
    ├── README.md
    ├── analysis/
    └── screenshots/

## Learning Outcomes

- Firmware extraction and inspection
- Static binary analysis
- Reverse engineering fundamentals
- Hardcoded credential detection
- Authentication logic analysis

## Disclaimer

This project was conducted in a controlled academic lab
environment for educational and cybersecurity research purposes.
The firmware is a simulated laboratory sample.
