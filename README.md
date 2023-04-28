# PQSA-GR-Traces

This repository contains a trace used in the PQSA-GR paper.

## Trace Format

Each line in a trace file represents a packet delivery opportunity: the time at which an MTU-sized packet can be delivered in the emulation. Accounting is done at the byte-level, and each delivery opportunity represents the ability to deliver 1500 bytes.