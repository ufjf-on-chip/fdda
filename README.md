# FDDA
## Project Overview: Fully Differential Difference Amplifier (FDDA)

This repository contains the design, schematic and simulation files for a Fully Differential Difference Amplifier (FDDA) circuit, optimized for the GlobalFoundries GF180MCU (gf180mcuD) 180nm open-source PDK. The design is built using the dockerized [IIC-OSIC-TOOLS](https://github.com/iic-jku/iic-osic-tools) environment.

This project is also a submission for the [SSCS Chipathon 2026](https://github.com/sscs-ose/sscs-chipathon-2026) program.

### Core Architecture

An FDDA is an advanced analog building block that extends the functionality of a standard Fully Differential Amplifier (FDA). Instead of a single differential input, the FDDA incorporates **two independent differential input pairs** to produce a fully differential output based on the algebraic difference between the two input signals.

By processing entirely differential signals from input to output, this architecture inherently maintains an exceptional Common-Mode Rejection Ratio (CMRR) and high immunity to common-mode noise. This versatility allows the FDDA to be easily configured for applications such as inverting/non-inverting amplifiers, instrumentation amplifiers, and active filters with minimal external hardware and without requiring well-matched resistor networks.
